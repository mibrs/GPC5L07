# Session 7 - More MAX8 with MIDI and introduction to sound synthesis with BEAP

*Remark: This session will be changed for future activities. The changes have not yet been applied.*

## Quick introduction to sound amplitudes and pitch/frequency
[Ableton Learning Synths](https://learningsynths.ableton.com/) is a website that explains the basics of sound synthesise in an interactive way. The key properties of sound you should know about are
- amplitude
- pitch and frequency, and 
- envelope. 
They are explained on this site. So, go there, get to know the meaning of the four key terms and then come back here and try out the patches. Just clone the repository, unpack its content and identify the patches (extension maxpat).

## Some more MAX patches with MIDI
You find several starter patches that you can try out and modify. Start with the patches containing MAX in their name. You may use Audacity to record one session using one of the patches. 

## Introduction to BEAP, and some patches
BEAP is a library of modules that make audio synthesis easier. Each module is built with many MAX and MSP objects, but the complexity is hidden and you only see an easy to use interface. 

Have a look at [this video](https://youtu.be/RhsQLUFLOAg) to get an idea what you can do with BEAP.

![BEAP Video 1](/media/221122BEAP1.png) 

When implementing the patch shown on the video, replace the ```MIDI IN``` module with a ```Keyboard``` module, you find it with BEAP/Inputs. For the outlets, hover over them with the mouse and their names and a short description will show up.
