---
title: Site Search
layout: page
# permalink: /search/
---

## Full metadata search:

<div class="">
    <input type="text" id="search" class="" placeholder="Enter your search term...">
    <table id="results" class=""></table>
</div>


<script src="{{ '/assets/js/lunr.min.js' | absolute_url }}"></script>
<script src="{{ '/assets/js/lunr-store.js' | absolute_url }}"></script>
<script>
/* initialize lunr */
var idx = lunr(function () {
  this.ref('id')
  this.field('title')
  this.field('text')

  //this.pipeline.remove(lunr.trimmer)

  for (var item in store) {
    this.add({
      title: store[item].title,
      creator: store[item].text,
      id: item
    })
  }
});

/* search function */
function lunr_search () {
  var resultdiv = document.getElementById('results');
  var searchBox = document.getElementById('search');
  var query = searchBox.value;//.toLowerCase();
  /* basic search that supports operators */
  var result = idx.search(query); 
  /* more fuzzy search, but doesn't support operators:
  var result =
    idx.query(function (q) {
      query.split(lunr.tokenizer.separator).forEach(function (term) {
        q.term(term, { boost: 100 })
        if(query.lastIndexOf(" ") != query.length-1){
          q.term(term, {  usePipeline: false, wildcard: lunr.Query.wildcard.TRAILING, boost: 10 })
        }
        if (term != ""){
          q.term(term, {  usePipeline: false, editDistance: 1, boost: 1 })
        }
      })
    });*/

  while (resultdiv.firstChild) { resultdiv.removeChild(resultdiv.firstChild); }
  resultdiv.innerHTML = '<p class="">' + result.length + ' Result(s) found</p>' + resultdiv.innerHTML;
  for (var item in result) {
    var ref = result[item].ref;
    var searchitem =
      '<tr>'+
          '<td class="">' +
            '<p class="h4"><a href="' + store[ref].url + '">' + store[ref].title + '</a></p>' +
            '<p class="ml-3">' +
            store[ref].text.split(" ").splice(0,20).join(" ") + '...<br>' +
            '</p></td>' +
      '</tr>';
    resultdiv.innerHTML += searchitem;
  }
}
/* init search box and get query string */
(function() {
  var searchBox = document.getElementById('search');
  searchBox.addEventListener('keyup', lunr_search, false);
  
  var queryString = window.location.search.substring(1).split("=")[1];
  if (queryString) { 
    searchBox.value = queryString;
    lunr_search (); 
  }
})();
</script>