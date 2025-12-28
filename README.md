# Racing-Macropad
The Racing Macropad is a compact, programmable input device based on the RP2040 microcontroller, designed for sim racing, gaming, and productivity use cases. It allows full key remapping, encoder customization, and RGB control. The rotary encoder can be used for functions such as brake bias, traction control, menu navigation, or volume control. The device uses Cherry MX–style mechanical switches and connects via USB. Its simple and modular design makes it ideal as a sim racing button box.

---
### Features:
* Compact 3×2 Key Matrix - 6 programmable inputs
* Rotary Encoder - programmable rotary encoder with push button
* 2x RGB LEDs - 2 LEDs for visual feedback
* 3D Printed Case

---
### CAD:
Designed using fusion. Everything fits together using 4x m3 screws and bolts:<br>

![Macropad](https://github.com/TudorPet/Racing-Macropad/blob/2d13686a754d29297048f042042274ddfdad6a47/CAD/cad.png)

---
### Schematic and PCB:
Designed with kicad. I ran DRC and got 0 errors, only a few dismissible warnings. <br>
![Schematic](https://github.com/TudorPet/Racing-Macropad/blob/2d13686a754d29297048f042042274ddfdad6a47/PCB/schematic.png) <br>
![PCB](https://github.com/TudorPet/Racing-Macropad/blob/2d13686a754d29297048f042042274ddfdad6a47/PCB/pcb.png)

---
### Firmware:
I wrote the firmware using QMK, which was definitely a change compared to what im used to. This was the part of the project that I was looking forward to the least (which may seem weird, as I do enjoy coding), and it turned out to be the most confusing one, too. With that being said, I am looking forward to learning more about QMK and improving.

---

### BOM:
* 1x Seeed XIAO RP2040 at €3.5 – €8.5 (~$4 – $9)
* 6x MX-Style switches at €0.50 – €0.60 (~$0.55 – $0.65) per switch, so €3 – €4 ($3.3 – $4.0)
* 1x EC11 Rotary encoder at €4 – €5 (~$4.5 – $5.5)
* 4x M3x16mm screws and 4x M3x5mx4mm heatset inserts at €1 – €3 ($1.1 – $3)
* 1x PCB €5 – €12 ($6 – $13)
* 1x 3D Printed case €5 – €15 ($6 – $17)<br>
These prices are a sheer estimation and, by no means, 100% accurate. Many of these components can be found priced very differently, depending on location and source. The estimated total ranges between €20 and €50 (huge difference, I know!), however I believe it would cost, at most, €30. A big part of the total is the 3d printed case, so the cost is greatly reduced if you own a 3D printer. 
---
### Notes:
This was my first time doing a project like this (and working with programs such as kicad and fusion - which i really enjoyed!). As someone familiar with algorithmics (that also occasionaly helps with repairing/building electronics), I found the design process really fun, however also a bit demanding for a person with so little experience. It took a little bit longer to finish the first version than i would have wanted, however im happy with the way it turned out. I want to keep working on it, implementing features such as syncing the leds to different titles and designing a stand compatible with different racing rigs.
