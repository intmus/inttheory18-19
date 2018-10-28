---
layout: chapter
title: Lesson 10b - Part-writing Errors
abc: true
---

In Unit 6b, we first looked at some basic rules for voicing a chord in a four-part style. These rules included:
- Voice-crossing
    - In this style, voices should generally not cross
    - Exception: alto and tenor may cross briefly if musically necessary
- Spacing
    - In a this style, the top three voices, soprano, alto, and tenor, should always be within an octave of the adjacent voices. To be more specific, there can never be more than an octave between *soprano* and *alto*. There can never be more than an octave bteween *alto* and *tenor*. 
    - There **can** be more than an octave between *bass* and *tenor*.
    - There **can** be more than an octave between *soprano* and *tenor*, and this creates two different types of voicings.
        - A *closed voicing* has **less** than an octave between *soprano* and *tenor*. 
        - An *open voicing* has **more** than an octave between *soprano* and *tenor*.
- Range
    - Each part must stay within the typical range for that voice/instrument?
- Doubling
    - **Do** double the root of a chord when possible
    - For triads, **do** double the fifth if necessary.
        - This is even preferable if the triad is in second inversion.
    - **Do not** double the third because it is a tendency tone. If this is doubled, it will force you to choose between the incorrect resolution of a tendency tone or unacceptable parallel octaves.
    - **Do not** double the seventh because it is a tencency tone. If this is doubled, it will force you to choose between the incorrect resolution of a tendency tone or unacceptable parallel octaves.
    - **Do not** double the fifth of a seventh chord. This would require omitting the root, third, or seventh, and none of these are expendable.

## Part-writing errors

In addition to the voicing rules, there are a number of standard part-writing errors that should be avoided as well:
1. Parallel perfect octaves or perfect fifths
2. Similar octaves or fifths (sometimes referred to as "direct", "hidden", or "exposed")
3. Unacceptable unequal fifths
4. Contrary perfect octaves or perfect fifths

Each of the four primary categories of part-writing errors are *symptoms* of voice-leading issues. If you understand the underlying voice-leading issues of each of these errors, you can find them more easily and avoid them in your own part-writing.

## Parallel perfect fifths and perfect octaves (PP5, PP8)

**Part-writing errors result from poor voice-leading. For example, look at the progression below and try to find our first major error: *parallel octaves*. Once you have found it, look to see if a voicing rule has been broken. If the voicing error is not fixed, is there any way to avoid the parallel octaves without incorrectly resolving a tendency tone?**

{% capture ex1 %}X:1
T:Parallel perfect octaves (PP8)
M:4/4
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [B,G,] [C,C]|]
w:C:I ii6 V7 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**Parallel octaves and fifths undermine the independence of lines, so you should always avoid them in this style. Listen to the following example, and try to locate the parallel perfect fifths aurally before you look through the parts.**

{% capture ex2 %}X:2
T:Parallel perfect fifths (PP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,A,] | [DG,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

**Once you have identified the voice that contains the PP5s, try singing the upper of the two voices, and then listen to the example again. Do you have a difficult time differentiating the upper voice from the lower of these two voices?**

## Contrary perfect fifths and octaves (CP5, CP8)

**Our next part-writing error, *contrary perfect fifths and perfect octaves* are simply an attempt to cover up parallel perfect fifths and perfect octaves by displacing one voice by an octave. The next two examples attempt to fix the errors from the first two examples on this page by displacing one voice of the parallel perfect intervals. Identify these by comparing them to the previous example (i.e. P) Notice that it creates multiple voicing and spacing errors as well as nearly unsingable parts!**

{% capture ex3 %}X:3
T:Contrary perfect octaves (CP8)
M:4/4
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [B,G,] [C,C,]|]
w:C:I ii6 V7 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}


{% capture ex4 %}X:4
T:Contrary perfect fifths (CP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,,A,] | [D,G,,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

## Unacceptable unequal fifths (UU5)

**The last two common part-writing errors have specific clauses tied to them that specify which voices are acceptable and unacceptable. The first, *unacceptable unequal fifths*, must occur between the bass voice and one of the upper voices. In the following example, find the *unacceptable unequal fifths* where a d5 moves to a P5. What is wrong with the voice-leading here?**

{% capture ex5 %}X:5
T:Unacceptable unequal fifths (UU5)
M:4/4
L:1/2
K:C
V:1
[cE] [Fd]| [dF] [cG]|]
V:2 clef=bass
[C,C] [D,A,] | [B,,G,] [E,C,]|]
w:C:I ii V6/5 I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

**Note that we will consider a P5 moving to a d5 as *acceptable* unequal fifths, because a P5 to a d5 does not require incorrect resolutions of tendency tones. There are some stricter versions of chorale part-writing that do not allow any form of unequal fifths.**

## Unacceptable similar fifths or octaves (US5, US8)

**The final common part-writing has many names, but we will use the term *unacceptable similar fifths or octaves*. This error can also be called "direct", "hidden", or "exposed". I prefer to use *similar* because it implies the motion like the other categories, but I also think that *exposed* does a fine job describing the effect. (I dislike the term *hidden* because students often confuse this with contrary fifths (or octaves), because the goal of contrary fifths is to "hide" parallel fifths.) *Unacceptable similar fifths or octaves* have the most restrictions. The conditions are:**
- They can only occur between the soprano and the bass voices.
- They require a skip of a third or more in the soprano voice.
- The two voices must move in similar (not parallel) motion.
- The second interval must be a P5 or P8.

**If any one of these conditions are not met, then there is not a part-writing error. Look at the following example to find an example of *similar octaves*. Once you have found it, look at the voice-leading around it. What does it do to spacing? Does it create more errors? Unacceptable similar octaves and fifths also often create melodies that imply different harmonies. To demonstrate, sing the melody alone. Do you hear it as C major or a different key?**

{% capture ex6 %}X:6
T:Similar octaves (S8)
M:4/4
L:1/2
K:C
V:1
[Ge] [AA]| [FA] [FB]| [c2E2]|]
V:2 clef=bass
[C,C] [CA,,]| [F,,C] [DG,,]| [C2C,2]|]
w:C:I vi IV V7 I{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

**As a final demonstration of the difficulties that these part-writing errors create, try to fix each of the part-writing errors on this page. What do you have to change? Do you get to keep the harmony? Voice-leading? Voicing? In trying to fix it, do you just create further errors?**

## Conclusions

## Parallel Perfect Fifths and Octaves

{% capture ex1 %}X:1
T:Parallel perfect octaves (PP8)
M:4/4
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [B,G,] [C,C]|]
w:C:I ii6 V7 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

The class found two examples of parallel perfect octaves in this example.
- between the soprano and tenor moving from ii<sup>6</sup> to V<sup>7</sup>
- between the soprano and tenor moving from V<sup>7</sup> to I

Almost all unacceptable examples of parallel octaves and fifths are due to poor voice-leading and voicings. In this case, the third of the five chord is doubled. This third is a tendency tone that should resolve upward by step, but in doing so, it creates parallel perfect octaves. The third never should have been doubled.

{% capture ex2 %}X:2
T:Parallel perfect fifths (PP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,A,] | [DG,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

In this example, the class found two examples of parallel perfect fifths:
- between the bass and tenor from I to ii
- between the bass and tenor moving from ii to V<sup>7</sup>

From this, we decided that the definition of a parallel perfect fifths/octaves is:
- when two voices have consecutive perfect fifths/octaves and move in parallel motion
    - it is not parallel perfect fifths/octaves if the intervals change voices (e.g. the first P8/P5 is between the soprano and tenor, but the second P8/P5 is between the soprano and alto)
- These are unacceptable between any two voices.

Parallel perfect fifths and octaves undermine the independence of the individual voices. Even after listening to the example with PP5s repeatedly, only one person in the class was able to distinguish the tenor voice. I then had the class look at the tenor voice and practice singing it in order to get the line into their ears. Even after doing this, they had trouble distinguishing between the two voices. This is even more pronounced if the chords are tuned using just intonation, because the upper note will blend into the overtone series of the lower note.
  
## Contrary Octaves and Fifths

{% capture ex3 %}X:3
T:Contrary perfect fifths (CP5)
M:4/4
L:1/2
K:C
V:1
[cE] [AF]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [D,,A,] | [D,G,,] [C,C]|]
w:C:I ii V7 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

Contrary fifths and octaves occur when trying to mask parallel perfect fifths and octaves. In the example above, the class identified the CP5s between bass and tenor voices between:
- the I chord and ii chord
- the ii chord and the V<sup>7</sup> chord

From this, we decided that the definition of a contrary perfect fifths/octaves is:
- when two voices have consecutive perfect fifths/octaves and move in contrary motion
    - it is not contrary perfect fifths/octaves if the intervals change voices (e.g. the first P5 is between the soprano and tenor, but the second P5 is between the soprano and alto)
- These are unacceptable between any two voices.

## Unacceptable Unequal Fifths

{% capture ex4 %}X:4
T:Unacceptable unequal fifths (UU5)
M:4/4
L:1/2
K:C
V:1
[cE] [Fd]| [dF] [cG]|]
V:2 clef=bass
[C,C] [D,A,] | [B,,G,] [E,C,]|]
w:C:I ii V6/5 I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

Unacceptable unequal fifths are one of the easier part-writing errors to understand, because we are actually focusing on only one voice-leading issue. We defined a UUF as any time a d5 between the bass voice and another voice moves to a P5. Because it has to fill all of these conditions, it is relatively easy to find compared to parallel and contrary fifths/octaves which are not acceptable between any voices.

The voice-leading issue that causes UU5 centers around the one naturally occurring d5 in the major scale: when `ti` is below `fa`. This is only likely to happen on a dominant harmony which means that this occurs typically on a V<sup>6/5</sup> chord or a vii<sup>o</sup> chord. The problem arises when `fa` does not resolve downward to `mi` in the next chord. This is an incorrect resolution of a tendency tone, and that is what creates the part-writing error.

## Similar Fifths and Octaves

Similar fifths/octaves occur when 1) the soprano and bass voices 2) move in similar motion to a 3) perfect fifth/octave, and 4) the soprano voice has a skip of a third or larger. You can see an example of this between the first two chords in this example.

{% capture ex5 %}X:5
T:Similar octaves (S8)
M:4/4
L:1/2
K:C
V:1
[Ge] [AA]| [FA] [FB]| [c2E2]|]
V:2 clef=bass
[C,C] [CA,,]| [F,,C] [DG,,]| [C2C,2]|]
w:C:I vi IV V7 I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

Similar fifths/octaves are sometimes called "exposed" fifths/octaves, and both of these terms demonstrate a key feature about the part-writing error. Obviously, they must move in similar motion, but the term "exposed" highlights the fact that these must occur between the outer voices. By having similar motion to a perfect interval in the outer voices, it creates the impression of a parallel perfect interval. Most importantly, the leap in the soprano typically creates a poor soprano line in which the melody outlines/implies an unintentional harmony. In the example above, if you sing the melody line without the harmony it outlines A minor instead of C major.