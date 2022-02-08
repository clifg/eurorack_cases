This is a Fusion 360 design file and STLs for a 3U eurorack case.

The f3d file has been parameterized so you can change the `case_width_hp` or `case_depth` to quickly make STLs for various case sizings. I put the 38hp case STLs here because that's the largest case I could print in one piece on my Prusa MK3.

If you change any parameters, be sure to check for warnings. I noticed that sometimes it would lose a few of the chamfered edges and I'd have to go re-add them.

The power supply I used for my case is the [MMI Modular USB Power](https://www.mmimodular.com/modules/usb-power/). In my 38hp case it's _just_ barely too long so rather than trying to cut off the end of the PCB I included a small cutout in the lid to make room. There are also screw posts in the base and a hole in the left side of the case for power entry. Inspiration for both the use of this power supply and the design of the lit attachment come from [GitHub - jepyang/eurorack-case: A small (42HP) and simple Eurorack case](https://github.com/jepyang/eurorack-case)

The rails are designed for M2.5 sliding square nuts, and you use the same square nuts in the three slots in the lid for joining the two sides of the case together. It's a snug fit but should be fine. If your printer makes the holes too tight and you don't want to ream them out a bit, go ahead and adjust the dimensions in the f3d file.

I used M2.5 8mm flathead screws for joining the lid to the case body, and M2.5 6mm pan head screws for attaching the USB Power to the bottom of the case.

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
