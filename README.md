# The metalFu(n)k 3D printer
Why call it that:
Used to be:
- A3D-One (When I was 16).
- MetalHunk (Because the full-metal frame is the best thing about it)
**Its now:**
- Metal Fuk. Because its a PITA. But being funky sounds kinder to it. 
------------

This 3D printer I started designing at the age of 16. Present day me is still suffering from the consequences of attempting to make such a thing without all the knowledge required. 
While it's been a very, very *edcuative* process, I'm now tryiong to make something useful out of it as it:
- Costed money to make (~400 USD then plus at least an aditional $100 while trying to make it work).
- Is a Pain in the 4$$.
- It would be nice to have a working 3D printer that I can proudly say "No one else in the world has this".
## Specs and Features:
- The sturdiest and most expensive frame you'll see in a while made fully of 2040 and 2020 T-Slot aluminum extrusion profiles.
- A BMG Bowden extruder.
- A custom (but full compromise) SLIM (and I mean **slim**) extruder I made for the Ender/CR Hotend.
- The novelty, antique and legendary **Ramps 1.4** which means it **runs on an Arduino Mega** <code style = "color : greenyellow">Will fix to support the Ender 3 -  4.2.7 Non-Silent Board OR the BIGTREETECH SKR Mini E3 V3.0).</code>.
- Marlin 2.0.1.
Double Z-Axis (Which is apparently a feature nowadays).
- <code style = "color : orangered"> Not a single V-Roller in sight besides being fully made in 2020 and 2040 T-Slot. Which is a problem. Will fix someday.</code>.

<img src="https://github.com/fgutep/MetalFunk/blob/master/images/HW_2024.jpeg" width="250">
> As of March 2024 it looks like this.
## Where am I with the development:
**Facts:**
- It has a decent and usable aluminum frame.
- It moves (It didnt use to).
- It does **not** caugh fire (it used to).
- It prints (Like *S*ugar *H*oney *I*ced *T*ea Tho).

### What I do not understand:
- The thing skips layers when printing anything above 40 minutes and starts shifting the object upfront making it unusable.
- Current of the motors. Only god and the guy who made them knows what current do they really use. While the *17HS3401* pancake Nema 17 motors i'm using have 1.2 Amps in their data sheet; they overheat a LOT when using that. Seem to run fine at 1/2 of the datasheet current and make a lot of noise anything below that.

<img src="https://github.com/fgutep/MetalFunk/blob/master/images/FaMMiniature.png" width="250">
> The Uploaded CAD File. Note that only includes metal frame and motors/endStops as every plastic piece needs to be re-designed from scratch.

## Goals and To-Do:
- **1. Re-Design and re-print every.single.piece.of.plastic**. By this I mean every piece of 3D printed material as it's a frankenstein adaptation that I made between the [Prusa Rework](https://reprap.org/wiki/Prusa_i3_Rework_Introduction "Prusa Rework") that I was comftable since it was my first 3D printer and what I managed to make of those parts *i.e. in TinkerCAD* as an adaptation to the V-Slot profile frame.
- **2. Put a better board in it** like the aforementioned 4.2.7 Non-Silent Board OR the BIGTREETECH SKR Mini E3 V3.0. As I suspect 90% of my problems have to do with using *The Defunkt RAMPS*.
- **3. Make it print Reliably** Which I suspect with a new board in place, and with the new parts should be easier.
- **4. Extruder** Make it look pro, and add a colling fan, light and better cable management.
- **5. Asthetics** It looks like a *MetalHunk* it should look nice, or at the very least funny. It should have a personality to it.
- **6. Add V-Roller Based Kinematics** it is Unaceptable for it to use smooth rods and linear bearing in the date and time we are in.
- **7. The SkyisTheLimit** Input shapping, really high speeds, really quiet, wireless conectivity, the ability to print upsuide down or sideways. Whatever. But first we need to meet every previous objective.

When will the objectives be met?
When they are. I Hope that By Summer 2024 I am at least by objective **#4**. But I am not putting a hard deadline on it either as I am an EE and CS student and work with *a lot* of teams, sideprojects and sidequests on a daily basis appart from this one.  

*Note-to-self:* If By August 2024 objective #3 is not met, the project might be scrapped as the value to keep going might be usustainable. 

##### Last update of the readme:
27/03/2024

### Man Hours:
| When | Who | How Many |
| ------------ | ------------ | ------------ |
|  2019-2020 | Fgutep  | 50+ Hours  |
| Dec 2023- Jan 2024  | Fgutep  |  20+ Hours |
| March 2024 (Holy Week) | Fgutep  |  10+ Hours |
|   |  Total ATM | ~80 Hours at Least  |

A free tip: Dont design, make and document a 3D printer as a 9th grade school project.

