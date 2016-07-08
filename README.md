# Basics
This repository is intended to facilitate as much remote configuration of the Lighting Rig as possible without physical access to the lights. We can program new Functions, setup virtual console, and even program the AKAI.  We'll also be able to visualize the effects of our changes using QLC+'s builtin "DMX Monitor", along with a special program for moving head visualization.

# Tools
* QLC+ version 4.10.4 (latest) http://QLCPlus.org -- Baisc DMX lighting configuration.
* Capture Atlas Student Edition (free) http://capturesweeden.com -- Simulation of moving heads
* GIMP or Photoshop -- Edit the PSD defining our AKAI panel layout

# Files
* Light Show.qxw: The QLC+ workspace started for the Nieboer Wedding.
* MovingHeadTest.qxw: The QLC+ workspace created for Mvoing Head tests.*
* MovingHeadTest.c2s: The 3D Visualization file for use with CaptureAtlas and the previous file.*

* Akai/Lighting Layout Scheme.psd:  Our planned layout for the AKAI
* Akai/Midi Layout.jpg: Describes the midi notes required to trigger different feedback on the AKAI.
* Akai/Akai Reference.jpg: Just so we can see what our AKAI actually looks like, in case that affects button placement.

* Fixtures/ :  Place these in your QLC+ Fixtures Definition folder before opening Light Show.qxw

*Because Capture Atlas Student Edition has limited fixtures we are unable to test our exact lighting rig with this software.  Instead, I have created a separate workspace for moving head tests, so we can more easily predict how our lights will behave.  Some tweaking will be needed, but this should greatly reduce the time required to actually configure our moving heads. NOTE:  Color for our moving heads IS simulated via QLC+'s DMX Monitor as well.

# Tutorials

I recommend reviewing the following 2 QLC+ tutorials when you have time.  They gave me several cool ideas for how we should configure this, and reminded me of several key features that will simplify our work.

* QLC Functions: https://www.youtube.com/watch?v=EbN2vi9SeVw
* QLC Positions (Moving Heads): https://www.youtube.com/watch?v=8-bgVX4uT2E 
