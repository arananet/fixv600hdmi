# fixv600hdmi
This little board allow to fix the hdmi connector of the Vampire V600 in case it's ripped off.

# Note

This is a work in progress, several testing must be made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

If you like the project or want to support it, you can buy me a beer or a KO-FI :) 
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H51MPWG)


# Images

<img src="https://github.com/arananet/fixv600hdmi/blob/master/images/top.png?raw=true" width="400">
<img src="https://github.com/arananet/fixv600hdmi/blob/master/images/bottom.png?raw=true" width="400">

# BOM 

| Part            | Value                   | Package                             |
| --------------- | ----------------------- | ----------------------------------- |      
|  R1             | 10k                   | 0805                                |
|  R2             | 10k                  | 0805                                 |
|  HDMI           | HDMI                  | HDMI CONNECTOR FOR PCB MOUNT                                |

## Note

The original Vampire V600 V2 (the firsts batchs) includes 27ohm resistors on the HDMI datalines and clock lines but the HDMI standard recommends to use 100nf capacitors instead, the V600 V2 uses 0603 100nf ceramic capacitors. So it will be better to remove those resistors and put the capacitors instead. 

# Updates

10/01/2020 Initial release.

# Gerber info

Gerbers are available on the gerbers folder.

# PCB information for manufacturers.

Layers : 2 layers

Dimensions : 17 x 18 mm

Blind/Buried Via: No

Material : Normal FR-4 Board TG140

Thickness : 1.2 mm

Surface Finish : HASL lead free

Silkscreen : Any color


# License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

