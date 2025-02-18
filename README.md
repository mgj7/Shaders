**WONKARCADE - The arcade monitor shader preset.**

The simple purpose of this shader preset is to mimic
the brightness, saturation, and glow, typical of arcade CRT monitors.

Copyright (C) 2025 Wonkastatic - this shader preset is free software; you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the Free
Software Foundation; either version 2 of the License, or (at your option)
any later version.

The individual shaders that make up this preset are the property of their
respective authors (see Attribution).

Notes:
- This shader preset works best with an output resolutions of 720p or higher
(1080p recommended)

- This shader preset works best with HDR monitors
(if possible enable HDR rendering on your monitor)

- This shader preset is fast and does not require high computing power
(tested effectively at 60fps on RPi4 or higher)

- The target model of this shader preset is specifically arcade monitors 
(Wells-Gardner, Zenith, and RCA tubes) not other types of CRT monitors
such as Sony Trinitron (PVM, BVM) or consumer CRT televisions. For this
reason this shader preset is intended to be used specifically with arcade games
and not with console or computer games

- One of the most common defects in shaders that imitate the image of CRT
monitors is that of making the image excessively dark and opaque due to the 
ypical effect of scanlines. This type of image quite closely resembles that of
domestic CRT televisions but is profoundly different from the image of arcade
monitors. Arcade games were known for their vibrant and bright colors.
In accordance with its purpose, this shader preset produces high levels of
brightness and saturation as a starting point. You are invited to try it in its original
formula. If you find the luminescence excessive, you can always adjust your
monitor settings so that the image quality better suits your preferences.

- This shader preset took hundreds of hours of testing and recalibration. The
technical aspect is not the most important part, however. No matter how much
effort you put into imitating the visual rendering of an arcade monitor, it will never
be possible to faithfully reproduce the image produced by a cathode ray tube on
an LCD panel. What I hope to have recreated is the feeling of an arcade monitor.
What I hope is that you can experience again the happiness and joy that that visual
experience offered. …the heart speaks in ways the mind can never understand :)

Attribution:

This shader preset is a patchwork of different software made by brilliant programmers
who decided to share and make their talent available to everyone. My deepest thanks
to them.

- zfast crt shader, (c) 2017 Greg Hogan (SoltanGris42) and (c) 2023 Jose Linares (Dogway), GNU GPL
  
- image-adjustment shader, by hunterk, public domain
  
- kavase blur, based on Ph.D Masaki Kawase's work and a shadertoy by Kubuxu

I hope I haven't forgotten anyone!
