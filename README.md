# 3d-print
Shared experiences with 3D printing.

Our printer is [Prusa i3 Mk3](https://shop.prusa3d.com/en/3d-printers/180-original-prusa-i3-mk3-kit.html).


## Printer setting - tunning

- We are using Raspberry Pi with [OctoPrint](https://octoprint.org) installed to access the printer remotely.

## Settings for material

- [FlexFill](#flexfill-98a)
- [CPE](#cpe-hg100-hm100)

### FlexFill 98A

**Pros**
+ Flexy
+ Really sturd

**Cons**
- Hard to print - easy bonds in extruder


**Slic3r**
- `Temperature: 240` / 40 °C (contrarry to Filamentum recomended 200-220 °C).
- `Filament / Max. volumetric speed: 1.1 mm3/sec`
- `Printer / Extruder 1 / Retraction length: 0 mm` (disabled)
- `Filament / Filament / Extrusion multiplier:  1.2`

**Printer**
- Slightly loosen tension screews on extruder ([see image](assets/flexfill-extruder-screews.jpeg)).
- Speed - I print on low speeds to have more success

**Other notes**
- As this material is hard to print with retraction enabled, it tends to make strings where possible. Look at [Slic3r Fighting Ooze](https://manual.slic3r.org/expert-mode/fighting-ooze) or try [Cura](https://ultimaker.com/en/products/ultimaker-cura-software) with `Travel / Combining mode = All`.
- Sticks just right, no special settings / glue is required
- link: [Filamentum flexfill 98A](https://fillamentum.com/products/flexfill-98a-traffic-black).
- I recomend to look at [3D Printing with Flexible Filaments](https://www.youtube.com/watch?v=fTJz6vMvtJ8) video.


### CPE HG100 HM100

**Pros**
+ stronger than PLA

**Cons**
- Sticks to bed so it is hard (if possible) to remove.
- Does not degrade in compost

**Slic3r**
- `Temperature: 260 / 85 °C` first layer, then `275 / 85 °C` (important! to prevent sticking)

**Other notes**
- You can use glue stick on cold bed to ease removal of finished product as described [here](https://ultimaker.com/en/resources/22229-how-to-print-with-ultimaker-cpe)



