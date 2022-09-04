# TH3D_v2.48_GEETECH_A20_FIX
This repository aims to fix latest TH3D (v2.48) bugs (like with leveling, offsets, print speed...) and also explains PROPERLY how to flash through ICSP using an Arduino Uno. The wiring diagram is also included.

## BEFORE YOU START ##

--- FLASH INFO ---
In some cases, flashing may require the GND ISCP pin to be shocked twice for flashing ability to unlock.
The wiring diagram `wiring-diag.png` to flash the ATMega2560 board through ISCP using and Arduino Uno is also included in the root folder of this repo.

--- COMPILATION INFO ---
You can either compile manually the firmware yourself, using the provided modified source code (or) simply use the compiled `firmware.hex` / `firmware.bin` that is provided in the root folder of this repo.

--- SOURCECODE INFO ---
ALL changes are annotated under the tag "BC:" (eg: "BC: Modified by BatchCode").

# PERSONNAL NOTE/ the following documentation has to be reworked later on.
## DONT FORGET TO ADD DOCUMENTATION ABOUT INSTALLING AND SETING UP ARDUINO IDE
--- DONT FORGET TO DOWNLOAD UG8 lib in IDE
--- FLASH UNO, using sample 11 "Arduino ISP" to remap ISCP pins
--- FLASH ATMEGA2560 after making sure the pin was shocked, DO NEVER try to force it unless you know what you are doing.
--- once flashing is FULLY done (check in prompt), you may disconnect everything

YOU CAN also use the provided firmware.hex



