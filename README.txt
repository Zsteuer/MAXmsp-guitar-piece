This is a patch I made for a school MAX class that is meant to help me play a two second piece for guitar and MAX. 

The first half is a blues that speeds up over time, and the second half, triggered by a chord that's written out in the patch after the first section, is more acoustic-feeling.

THE FIRST SECTION HAS SOME "AI" PROPERTIES:

- There are two different blues melodies that are twelve bars long which are loaded as midi files into the patch. 

- Each of them also come preprogrammed with a list of places in the chart where the phrase ends. 

- When once phrase ends, MAX randomly “decides” to either switch to the new melody or randomly stay on the current melody. There is a 50/50 chance of either. 

- It also makes a decision whether to switch between the two FM synths I made or not. 

- However, before playing the phrase it settles on, it checks to see how loud the guitar volume is. If the guitar volume is sufficiently loud, the next phrase will not play. 

- At each phrase ending, the drum pattern also switches between one of four beats, although not at a rate more often than once per second. 

- Thus, there are 16 possible configurations at any given moment, with four drum beats, two synths, and two melodies. 

- If one considers the silence of both melodies, as triggered by the guitar, to be another possibility, then this number is 24.

Also, BOTH sections have timed guitar effects.

There's lots of other comments in the patch that explain it.

A zipped sigmund abstraction is included as a zip. I use it in the patch for pitch tracking (to trigger section 2).

