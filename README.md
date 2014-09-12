#Shadow Ball#

Shadow Ball is a game in which you must shoot and kill the never ending armies of the four elements. To the north there is the Air army, to the east the Water army, to the south the Earth army, and to the west the Fire army. Each level adds increasingly more enemies in each room. But you have one advantage: The spirit Orb, providing an endless supply of golden power. But watch out for the deadly mist that protects the enemy forces, and remember to make regular trips back to the Orb to recharge.

This is an an entry for [js13kGames](http://js13kgames.com) 2014. The theme for this year was "The Elements: Earth, Water, Air and Fire". This is represented in Shadow Ball by the four enemy types, which each have a distinctive colour related to the Element they represent. The World Map is split into four main enemy zones relating to each Element, and the status line tells you which of these zones you are in.

**Final Size:** TODO

#Controls#
**Move:** Arrows 
**Jump:** SPACE
**Fire:** M
**Absorb:** N
**Push:** B
**Pickup/Drop:** V
**Pause:** P  

#Notes#
Best played in Chrome, on a reasonably fast computer with a semi-decent graphics card. Works reasonably well in Firefox as well.

I was hoping to build this game within a single canvas, but I ran into a number of rendering issues with the canvas approach, even though I followed the usual advice about using requestAnimationFrame, etc. I decided to continue by prototyping with DOM sprites instead since it was performing a lot better at that time. Then halfway through the competition, I realised that my browser wasn't using hardware acceleration for the canvas. So I spent a few days switching it back to canvas, then tried forcing the browser to use hardware acceleration, and ironically it performed significantly worse than when the canvas wasn't using hardware acceleration. I even resorted to buying a new graphics card but DOM sprites still seemed to be performing better. I think it's something to do with Chrome on Linux and the acceleration support for the canvas, and possibly drivers. So to stop burning up time, I ended up switching it back to DOM sprites again and continued with that approach. It is possible it might be a little jerky on slower modern PCs, but it runs smooth on my i7 4771. Hopefully you'll all be able to enjoy it.

#Credits#
**Created By:** Lance Ewing
**Original Music By:** Lance Ewing
**Sound Effect Library:** [JSFXR](https://github.com/mneubrand/jsfxr) by Markus Neubrand
**Music Synth Library:** [SoundBox] (http://sb.bitsnbites.eu/) by Marcus Geelnard
**Inspiration:** [King's Quest (game)](http://en.wikipedia.org/wiki/King's_Quest), [Wheel of Time (books)](http://www.tor.com/features/series/wheel-of-time-master-index), [Mistborn (books)](http://brandonsanderson.com/books/mistborn/), [Avatar: The Last Airbender (TV/Movie)] (http://en.wikipedia.org/wiki/Avatar:_The_Last_Airbender).

#Screenshots#

TODO
