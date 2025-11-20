# ESP32
I'm new to ESP32, microcontrollers, assembler, all of it. Consider this an ongoing compilation of links for my convenience/reference as I learn.

## ESP32-S3
- [esp32-assembly (Github)](https://github.com/AdityaNG/esp32-assembly) - I've forked this.
- [ESP32-S3 Technical Reference Manual Version 1.7 from Espressif (PDF)](https://documentation.espressif.com/esp32-s3_technical_reference_manual_en.pdf) - documentation to the tune of 1,500+ pages...
- [ESP32-S3 data sheet PDF](https://files.seeedstudio.com/wiki/SeeedStudio-XIAO-ESP32S3/res/esp32-s3_datasheet.pdf)
- [ESP32-S3 ULP coprocessor instruction set](https://docs.espressif.com/projects/esp-idf/en/stable/esp32s3/api-reference/system/ulp_instruction_set.html)

## M5stack Cardputer v.1.1
- [M5stack Cardputer v.1.1](https://shop.m5stack.com/products/m5stack-cardputer-with-m5stamps3-v1-1) - This uses ESP32-S3. I was able to get it to "talk" to a **microSD SDHC card** (32GB) for storage but *not* to SDXC.
- [M5stack Cardputer v.1.1 documentation](https://docs.m5stack.com/en/core/Cardputer%20V1.1)
- [M5Burner](https://docs.m5stack.com/en/uiflow/m5burner/intro) - for burning firmware. I started by flashing **M5Launcher Cardputer & ADV 2.6.3**. From there, you can e.g. *turn down the beeping noises* from **Settings**. After setting up wi-fi, I was also able to download more apps via the cloud. Right now, I'm using VoidNoi's **BadCard** as a "text editor" storing to microSD!
- [VoidNoi's BadCard on Github](https://github.com/VoidNoi/BadCard/)

## Forth for ESP32?
Another goal unlikely to be realized. I was unable to figure out how to compile and flash a working binary for [ESP32Forth](https://esp32forth.appspot.com/ESP32forth.html), which I *think* doesn't innately support ESP32-S3 (as opposed to ESP32-S2).

- [A Beginner's Guide to Forth by J. V. Noble](https://galileo.phys.virginia.edu/classes/551.jvn.fall01/primer.htm)
- [Forth Lessons](https://wiki.laptop.org/go/Forth_Lessons)
- [masmjf - a NASM assembler port of JONESFORTH](https://ratfactor.com/repos/nasmjf/index.html) - also notable since it mirrors the entirety of JONESFORTH, whoes original repository/text seems to have gone the way of link rot. (JONESFORTH is in the public domain.)
- [Bradford J. Rodriguez: Moving Forth and other papers](https://www.bradrodriguez.com/papers/index.html) - Moving Forth discusses Forth kernel implementation by way of i386 as an example.
