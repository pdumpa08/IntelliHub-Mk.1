---
title: "IntelliHub Mk.1"
author: "Praneet"
description: "A USB Hub for people stuck with just USB C"
created_at: "2025-07-19"
---
<em>Total Time Spent: 14.00h</em>

# July 19th: Designed Schematic and PCB!

Today, I researched and found the idea and basic design idea for my project. In addition, I found a hack club jam (https://jams.hackclub.com/batch/usb-hub) that would be extremely useful during the process. It wasn't exactly what I wanted, but then it shouldn't be exactly the same. I planned to add USB c functionality to make the hub work for my purposes (Macbook Air...).

I then moved on to creating the schematic. After finding the necessary parts, the wiring was pretty simple, using the principles the jam taught (grounding, ideal power combinations, etc.). Once I had completed the schematic, I moved on to making my PCB design. This process was singificantly harder in that I had never before connected more traces than I had to today. But eventually, with a lot of new techniques found, I completed the traces.

![Schematic](https://github.com/pdumpa08/IntelliHub-Mk.1/blob/main/assets/Schematic?raw=true)
![KiCAD PCB](https://github.com/pdumpa08/IntelliHub-Mk.1/blob/main/assets/KiCAD_PCB?raw=true)

**Total time spent: 5.00h**

# July 20th P2: Had to migrate the PCB...

Nooooo! Today, I attempted to finalize my PCB design. However, it turns out I made a fatal flaw. I used KiCAD to build my PCB using LCSC parts (imported using a plugin). To say the least, it did not work. The footprints were all wrong and I had 23 DRC errors when I finished tracing and checked... Well, I tried to transform it into an EasyEDA project, but the footprints supplied by the plugin simply wouldn't show up. So, I spent many a hour reconstructing my PCB design. It was cathartic in a sense. It was mind-numbingly annoying in another.

![EasyEDA PCB](https://github.com/pdumpa08/IntelliHub-Mk.1/blob/main/assets/PCB?raw=true)

**Total time spent: 4.00h**

# July 21st: CADding and Submission!

FINALLY! CAD! I'm new to hardware and so haven't worked with CAD or PCB design too much, but in my experience I found PCB design to be a lot more fun. This time, however, I found myself looking forward to the CAD. And it was pretty fun. Once I had figured out my dimensions, it was fairly smooth sailing from there to make the case. I modeled it after my HackPad design and used similar techniques. One thing that did stump me was how to include the actual PCB for the full image requirement, but in the end I just used the .Obj file and scaled it accordingly using measure on both EasyEDA and Fusion 360.

![CAD](https://github.com/pdumpa08/IntelliHub-Mk.1/blob/main/assets/Full?raw=true)

**Total time spent: 5.00h**