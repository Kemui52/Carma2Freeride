# Root Folder

## Cheat Mode to WetWet EXE Patch

Swops the cheat mode and 800 credits cheats with each other because I can't remember to lap my love pump.

SW version is untested, but theoretically correct.

The hex edits themselves, if you need to know:

HW exe:

``0x18EB88: 80 2E 44 00 00 00 00 00``

``0x18EBB8: 80 15 44 00 B9 78 4E 56``

SW exe:

``0x189D80: 60 2F 44 00 00 00 00 00``

``0x189DB0: 60 16 44 00 B9 78 4E 56``

--

Found thanks to:

https://rr2000.cwaboard.co.uk/blog/index.php?post/Some-words-about-hex-refs-of-the-powerups
