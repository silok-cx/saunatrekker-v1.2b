SAUNATREKKER v1.2b - 2025 by Silok/sgp - Robert Katsenos
--------------------------------------------------------
It's related to the design and behavior of the Amiga Protracker Series from the 1980s/90s.
Not an exact clone but it takes the spirit of the Aera.

It has been completely written in Cerberus-x: https://www.cerberus-x.com/
The sourcecode relays on the Gnu Public License v3: https://www.gnu.org/licenses/gpl-3.0.html.

Binaries download Page: https://silokkis.blogspot.com

How to use it ?

You can use it like all the Sound/Noise/Protrackers from the Amiga etc.
With one restriction. It's working only with the Amiga VBlank speed,
not with the Tempo(BPM) timing.

Additionally there are some special functions.

Function Keys
-------------
F1-F2 = Octave Change
F4 = Change Stereoseperation 0/50/100
F5 = Change Key-Map US/DE
F7 = Copy Block
F8 = Paste Block
F9-F10 = Turn on/off Channels

Copy & Paste Tracks
-------------------

Hold the SHIFT-Key and navigate with the cursor or mouseroll up and down.
Press F7 for copy a Block. Navigate to the Track and row you want to paste it and press F8.

Transpose Notes
---------------

Navigate into the Track you wish to transpose the notes. Press plus or minus to
transpose the notes up and down.

Config.ini File
---------------

You can change a bunch of parameters in this file.

The configfile format is as follow:

scale; - INT = Multiplies the scaling like 1x 2x etc. ( Example for 2x scaling: 2; )
B,G,R; - INT = from 0 to 255 - Which are Blue,Green,Red ( Gui Color1, a grey shade for default )
B,G,R; - INT = from 0 to 255 - Which are Blue,Green,Red ( Gui Color2, a grey shade for default )
B,G,R; - INT = from 0 to 255 - Which are Blue,Green,Red ( Gui Color3, a grey shade for default )
R,G,B; - INT = from 0 to 255 - Which is the Gui Font ( it's just black for default )
R,G,B; - INT = from 0 to 255 - Which is the Tracks-Font color ( a blue color for default )
R,G,B; - INT = from 0 to 255 - Which is sample drawing and stereoscope color.
R,G,B; - INT = from 0 to 255 - This is the background color.
R,G,B; - INT = from 0 to 255 - This is the Vumeters tintcolor ( It changes the appearence of the Vumeters color )

Which Protracker Commands are NOT supported:
--------------------------------------------
7xy - Tremolo
9xy - Sample offset
E3x - Glissando control
E4x - Vibrato waveform
E7x - Tremolo waveform
E9x - Retrigger note x tick
EEx - Pattern delay

10/24/2025 - Update since v1.0b:
--------------------------------

- Fully integrated playroutine. ( not all effect-commands are implemented )
  no external player needed.
- Samplechange bug removed.
- False noteplay on first Song-playstart removed.
- US/DE Keymap support included.

10/27/2025 - Update since v1.1b:
--------------------------------

- Stereoscope retrigger bug at first songplay fixed
- Stereoscope 3xx retrigger removed
- Sampledisplay retrigger on 3xx removed
 
 
