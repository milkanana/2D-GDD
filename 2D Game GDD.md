#2D Game Design Document

[TOC]

## Project Overview
Description....

##Ideation
**Core Mechanic**: compare edges to switch platforms
**Platform movement**:
> Initial Ideas:
> [1) Rows](https://www.dropbox.com/s/pssg9au6k6l2g4p/Untitled-1.gif?dl=0) [2) Set Paths](https://www.dropbox.com/s/rdwix1552v4xhdu/Untitled-2.gif?dl=0)



##Interface
##Mechanics
##Controls

**Keyboard Controls:**
up/down: choose edge
left/right arrow: choose jump direction
Space: jump


**18.07.:** Edit to use controls for tablet

##Programming/Technical Solutions
**Core Mechanic**:choose edge --> wait for current platform and target platform's  --> change platforms --> repeat

**Scripts**: 
Player Script,
--> Rotate when choosing platforms...

Platform Movement,
--> Boids Flocking
Dragonfly,

etc.
......

**Features**:
platforms drifting out of visible screen
Enemies sinking platforms
</br>


![Prototype Screenshot](http://orig03.deviantart.net/6ea9/f/2017/179/b/c/screenshot_by_mxlk-dbebnxo.jpg)

## Visuals

### Conception

####Artstyle

![Prototype Screenshot](http://orig03.deviantart.net/6ea9/f/2017/179/b/c/screenshot_by_mxlk-dbebnxo.jpg)
<div style="text-align: right"> *Original Screenshot (Prototype)*</div>

##### First Fake Screenshots
Each team member creates a vision for the prototype

![Fake Screenshot Daniel](http://orig06.deviantart.net/dddc/f/2017/179/b/a/fakescreenshot_daniel_by_mxlk-dbebnyb.png)
<div style="text-align: right"> *Fake Screenshot (Daniel)*</div>

> **Feedback: **
> **+** 'height' emphasizes danger, good for parallaxing, player character seems helpless;
> **-** concept more befitting of 3D game, too much movement, lines too thick, interfere with core mechanics;

</br> <!-- leerzeile -->

![Fake Screenshot Katharina](http://orig09.deviantart.net/9b5f/f/2017/179/7/7/fakescreenshot_katharina_by_mxlk-dbebny4.jpg)<div style="text-align: right"> *Fake Screenshot (Katharina)*</div>
>**Feedback**: 
>**+** contrast, textures, color selection, lineart, functionality; 
>**-** pink gradient too strong; player's artstyle does not fit at all; 

</br>

![Fake Screenshot An](http://orig13.deviantart.net/732d/f/2017/179/a/5/screenshot_2_by_mxlk-dbebpm0.jpg)
<div style="text-align: right"> *Fake Screenshot (An)*</div>

>**Feedback:**
>**+** colors, visual hierachy, functionality, contrast, lively, dragonflies have potential for animation and sound;
>**-**  background too dark, layers of stones unclear, player's platform seems lifeless;

</br>

> **Overall Feedback**:
> **+** good use of geometrical shapes, colors and contrast, visual hierachy, 
> **-** player characters might not be ideal, 
> **Suggestions**:
> player character: frog, seal, any kind of animal whose top view is interesting; water surface reflection;
> Don't mix/combine the two (An/Katharina) styles, choose one for to proceed with next step; 

</br>

> **Conclusion**: 
> The whole group agreed to go with An's screenshot, as it was the most appealing.

</br>

#####Fake Screenshot Iteration


#####Fake Screenshots 2

![](http://orig10.deviantart.net/d234/f/2017/179/1/f/02characters_katharina_by_mxlk-dbebnyi.jpg)
<div style="text-align: right"> *Player Design (Katharina)*</div>
![](http://img11.deviantart.net/9c72/i/2017/179/9/3/02fakescreenshot_an_katharina_04_by_mxlk-dbeby1q.jpg)
<div style="text-align: right"> *Fake Screenshot 2 (Katharina)*</div>
![](http://orig08.deviantart.net/ae93/f/2017/179/f/1/02fakescreenshot_an_katharina_03_by_mxlk-dbeby1w.jpg)
<div style="text-align: right"> *Fake Screenshot 2 (Katharina)*</div>
![](http://img03.deviantart.net/dd9e/i/2017/179/2/9/02fakescreenshot_an_katharina_07_by_mxlk-dbeby0y.jpg)
<div style="text-align: right"> *Fake Screenshot 2 (Katharina)*</div>

![](http://orig15.deviantart.net/4dd8/f/2017/179/d/b/screenshot_2_revised_by_mxlk-dbebnxx.jpg)
<div style="text-align: right"> *Fake Screenshot (An)*</div>


</br>
 
>**Feedback**:
>**+** broken oulines, stones more visible;
>**-** player character too unfriendly (aggressive)--> too detailed;
>**Suggestions**:
>player character: ladybug, 



####Animation

**Player**
![Begin flight](http://orig12.deviantart.net/0926/f/2017/199/6/c/02spritesheet_ladybug_startflight_by_mxlk-dbgralm.png)
<div style="text-align: right"> *Spritesheet (open wings)*</div>
![flight](http://orig12.deviantart.net/96a8/f/2017/199/6/6/02spritesheet_ladybug_flight_by_mxlk-dbgralr.png)
<div style="text-align: right"> *Spritesheet (flight)*</div>
![End of flight](http://orig10.deviantart.net/a5a7/f/2017/199/6/6/02spritesheet_ladybug_endflight_by_mxlk-dbgram5.png)
<div style="text-align: right"> *Spritesheet (close wings)*</div>
![Idle](http://orig09.deviantart.net/5bb1/f/2017/199/2/e/02spritesheet_ladybug_waiting_by_mxlk-dbgralg.png)
<div style="text-align: right"> *Spritesheet (idle)*</div>

**Water**:
Glistening: Unity, Particle system
Caustics: Layering textures


####Sound
**To Do**: 
SFX: (Sound Effects), cbanging platforms, dragonflies
FOL: (Foleys), wings flapping,
BG: (Background Sounds), water sounds(?)
MX: (Music Effects), Not needed
DX: (Dialogue), Not needed 


##Project Management

#####WorkFLOW Planning:

**Requirements**:

Assets:
1. platforms sprites
2. player character sprite
3. player's tool sprite
4. enemy sprite
5. background (stones, water reflection, line details)


**Task division: **
"Leader" Katharina/An Art and Animation, Daniel/An Programming, Daniel Sound; 


**Sprites**: 
Player + tool: Katharina
Enermy(cleaning): An 
Background: An
Additional: An

**Animation**:
Player: Katharina
Enemy: Katharina
Background: An
Additional: An
Effects: Daniel

**Materials**: --
Feedback: get Feedback for player character;
</br>


####To DO
|| Backlog |To Do  | in Work|  Done|
|------|--------|--------|--------|------|
|**Programming**|       | |      |
||pick ups |        |Platform movement |Prototype|
|| reverse flow       |Prototype clean up| |      |
|**Art related**|||||
||        |        |Artstyle| Setting/Narrative     |
||        |  Sprites      |        |      |
|||Animation|||
|||Sounds|||
|**Documentation**|||||
|||GDD|||
|||One Pager|||
|||Lookbook|||
|||Gameplay Videos||||

##Reflection

## Lookbook