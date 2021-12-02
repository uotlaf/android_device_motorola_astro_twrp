# TWRP Device configuration for Motorola One Fusion
#Moved to https://github.com/sdm710-motorola/android_device_motorola_astro_twrp
## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (2x2.2 GHz Kryo 360 Gold & 6x1.7 GHz Kryo 360 Silver)
CHIPSET | Qualcomm SDM710 Snapdragon 710
GPU     | Adreno 616
Memory  | 4 / 6 GB
Shipped Android Version | 10
Storage | 64 / 128 GB
Battery | 5000 mAh
Dimensions | 165 x 75.9 x 9.4 mm
Display | 720 x 1600 pixels, 6.5" IPS LCD
Rear Camera  | 48 MP (f/1.7, wide, PADF) + 8 MP (f/2.2, 118º, ultrawide) + 5MP (f/2.2, macro) + 2MP (f/2.2, depth) HDR
Front Camera | 8 MP (f/2.0)

![Device Picture](https://fdn2.gsmarena.com/vv/pics/motorola/one-fusion-1.jpg)


### Kernel Source

Check here: https://github.com/uotlaf/android_kernel_motorola_sdm670

### How to compile

```sh
. build/envsetup.sh
export LC_ALL=C
lunch omni_astro-eng
mka recoveryimage
```

### Copyright
 ```
  /*
  *  Copyright (C) 2013-21 The OmniROM Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```
