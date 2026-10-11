# minigame 2
## Devlog
1. I actually had an error that was a pretty easy fix but had me scratching my head for a little bit. On the first step when it was telling me to subtract time from _timeLeft, I started typing before I got an error straight away. It told me
to my sure to clarify what _timeleft was and so I was like, "oh okay that makes sense, it's a float so I'll put float before it." Upon finishing it, I kept getting these errors about misusing _timeLeft and they really confused me. It was only
on looking outside my statement where I saw it was already declared and when I changed my line, the errors went away. In any case, I learned to look at the rest of the code before writing and also don't be too hasty to go with the auto suggestions.
2. My guess is that since it goes through the sprite renderer, it changes the color of the object no matter what sprite is selected. The period is for connecting the color to the sprite renderer class I'm pretty sure and the new creates a new instance
of the object, my guess is that this color is saved to be applied to other things like to change a character's hair color or something.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
