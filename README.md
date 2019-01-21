# 3d-print
Shared experiences with 3D printing.

Our printer is [Prusa i3 Mk3](https://shop.prusa3d.com/en/3d-printers/180-original-prusa-i3-mk3-kit.html).


## Printer setting - tunning

- We are using Raspberry Pi with Octo print installed to access the printer remotely.

## Settings for material

### [filamentum flexfill 98A](https://fillamentum.com/products/flexfill-98a-traffic-black)

#### Properties
+ This material is sturdy and a little flexy.   
- Easy bonds in extruder.

[Here](https://www.youtube.com/watch?v=fTJz6vMvtJ8) is a great video about problems with this filament.


#### Software settings

- Temperature 240 / 40 °C (the temperature range on Filamentum web page is
  200-220 °C, but it does bond too often in extruder in my printer).
- Filament / Max. volumetric speed = 1.1 mm3/sec
- Printer / Extruder 1 / Retraction length = 0 mm (disabled)

#### Printer preparation

- Slightly loosen tension screews on extruder.
- Bed - this material sticks just right, no special settings required
- Speed - I print on low speeds to have more success


