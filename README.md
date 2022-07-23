# Touch-designer
Some of the various Touch designer patches I'm working on


as I add more patches they will get organized into types


mostly we will be looking at 

utility modules, 
LZX module emulations and 
things of my own creation


The goal is to be able to look at the inner workings of video synthesis concepts and workflows to gain a better understanding overall

all modules will have custom control panels so they can easily be mapped in anyway you prefer



**Dreamweaver**
* quad oscillator cluster /> ramp creator > ramp effector
* the quad osc can be used to modulate the ramps 
* then there are lots of ways to change the ramps (mirror, color, feedback etc..)
* this is our first TD video synth voice


**FKG3**
* this is an emulation of the LZX FKG3 module
* FG,BG,Key RGB compositing



**Topogram**
* A simple topogram emulation for now. There is still work to be done but as far as a cascading set of keyers this will work!


**RGBbander**
* Our first colorizer. This made of fairly simple parts but can do a whole lot of color transforms

**VVeb**
* this started out as a memory palace emulation and is growing to be a whole lot more.
* https://www.youtube.com/watch?v=lI00GCLIrLw a video overview of the patch

**XY Gesture looper**

X Y inputs for your controls 
X&Y effect switch - choose between control input, S&H or LFO blend
X&Y LFO Freq - frequency of lfos
X&Y LFO Blend - blends between X&Y input controls and associated LFO
X&Y gesture mode - turns on/off gesture recording
record loop - records from on until off and automatically loops
play loop - starts and stops loop playback 
speed of loop  - recording a loop at .5 on the slider will allow you to make the loop faster or slower all the way down to stopped
lag amount - sets end of chain lag


the X&Y effect switches go into the gesture looper so you can loop control input, S&H or LFO blend signals





**coming in the future**

* arch / DSG3 (core concepts are worked out)
* 4 quadrant multiplier (a building block that gets used all over the place)
* video looper (already done just needs cleaning)
* video looper / temporal displacement (cleaning)
* Scrawl (our rpi video painter) needs a full rebuild
