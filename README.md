# ThumbsUpUnsplitV2
Multilevel 44 Key Ergonomic Keyboard.
V2 puts the fourth row one level up.

The board uses Kailh Choc hot-swap switches.

//TODO Pictures to be replaced.

![Main view](https://github.com/ak66666/ThumbsUpUnsplit/blob/main/Photos-001%20(12)/20220219_191523.jpg)
![Three levels are visible](https://github.com/ak66666/ThumbsUpUnsplit/blob/main/Photos-001%20(12)/20220219_191651.jpg)
![](https://github.com/ak66666/ThumbsUpUnsplit/blob/main/Photos-001%20(12)/20220219_152609.jpg)
![](https://github.com/ak66666/ThumbsUpUnsplit/blob/main/Photos-001%20(12)/20220219_184854.jpg)
![](https://github.com/ak66666/ThumbsUpUnsplit/blob/main/Photos-001%20(12)/20220219_184909.jpg)
![](https://github.com/ak66666/ThumbsUpUnsplit/blob/main/Photos-001%20(12)/20220219_191540.jpg)
![](https://github.com/ak66666/ThumbsUpUnsplit/blob/main/Photos-001%20(12)/20220219_191637.jpg)

# Firmware
                                                               
The board uses Planck rev4 software with one pin replaced - it is needed for Cirque trackpad.
To make it work - modify \qmk_firmware\keyboards\planck\config.h, replace the pin definition with this one:

#define MATRIX_COL_PINS { D7, B4, D6, D4, F7, F6, F5, F4, C7, B0, F0, F1 }



