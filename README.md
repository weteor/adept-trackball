

## xiao-mod changes:

- newly routed pcb ( [KiCAD files](hardware/electronics/adept_xiao) )
  
  - xiao rp2040 controller
  
  - two layer
  
  - components needed:
    
    - 1x seeed xiao rp2040 controller
    
    - 1x xc6206P18 LDO in SOT-23 package
    
    - 1x 100nF capacitor - 0805
    
    - 2x 1uF capacitors - 0805
    
    - 1x 10uF capacitor - 0805
    
    - 1x 39Ohm resistor - 0805
    
    - 1x 10kOhm resistor - 0805
    
    - 1x PMW3360DM-T2QU sensor (same as in orig ploopy adept)
    
    - 6x Omron D2LS-21 switches (same as in orig ploopy adept)

- modified case to support xiao dimensions ( [FreeCAD and STL files](hardware/mechanicals-xiao) )

- firmware modifications to support xiao pinout, copy [folder](firmwares/xiao_mod) to your Vial firmware folder under keyboards/ploopyco and build with: 
  `make ploopyco/adept_xiao:vial`
  or use the  `ploopyco_adept_xiao_rev1_001_vial.uf2` in the folder directly and configure the buttons in vial
  
  

---

# The Ploopy Adept Trackball

![The Ploopy Adept Trackball](adept.jpg)

By some stroke of luck, you've made your way here. The Ploopy Adept Trackball. Your life will never be the same.

This repository contains all of the design and production files necessary to make a Ploopy Adept Trackball. We've also included some kick-ass documentation in the Wiki on how to get it made, assemble it, and program it.

What are you waiting for? Your new life awaits.

## QMK?!

Kits bought from the [Ploopy store](https://ploopy.co/product-category/trackball/adept/) come with QMK and VIA preloaded. Check out the Wiki for instructions on how to load new firmware onto your device. (It's super easy!)

The firmware hex file that ships with all Adepts is included in this repository as well, as `ploopyco_madromys_rev1_001_via.uf2`.

## Under what license is this released?

As per QMK's licensing requirements, the firmware for the Ploopy Adept Trackball is released under GPLv3. Hardware design files, including electronics and mechanical files, are released under OHL CERN v2-S. Check the respective directories for full license text.
