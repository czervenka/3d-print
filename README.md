# 3d-print
Shared experiences with 3D printing.

Our printer is [Prusa i3 Mk3](https://shop.prusa3d.com/en/3d-printers/180-original-prusa-i3-mk3-kit.html).


## Printer setting - tunning

- We are using Raspberry Pi with [OctoPrint](https://octoprint.org) installed to access the printer remotely.

## Settings for material

### FlexFill 98A

[Filamentum flexfill 98A](https://fillamentum.com/products/flexfill-98a-traffic-black).

[Here](https://www.youtube.com/watch?v=fTJz6vMvtJ8) is a great video about problems with this filament.

**Pros**
+ Flexy
+ Really sturd

**Cons**
- Hard to print - easy bonds in extruder


**Slic3r**

- `Temperature: 240` / 40 °C (the temperature range on Filamentum web page is
  200-220 °C, but it does bond too often in extruder in my printer).
- `Filament / Max. volumetric speed: 1.1 mm3/sec`
- `Printer / Extruder 1 / Retraction length: 0 mm` (disabled)
- As this material is hard to use with retraction it really tends to make strings where possible. Look at [Slic3r Fighting Ooze](https://manual.slic3r.org/expert-mode/fighting-ooze) or try [Cura](https://ultimaker.com/en/products/ultimaker-cura-software) with `Travel / Combining mode = All`.

**Printer**

- Slightly loosen tension screews on extruder.
- Speed - I print on low speeds to have more success
- ... nothing else, this material sticks just right, no special settings / glue is required

