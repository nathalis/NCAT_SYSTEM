# NCAT_SYSTEM
NCAT SYSTEM is a new version of esp32 applications (3 in 1) including NES emulator, mp3 player, 1 Mhz oscilloscope. New modular hardware is used. The device supports microSD cards, Composite TV out, some USB keyboards and much more.

Also You need disable fix PSRAM cache: 
in file (for example): C:\Users\ {MYUSERNAME} \AppData\Local\Arduino15\packages\esp32\hardware\esp32\1.0.3\boards.txt

```shell
#esp32.menu.PSRAM.enabled.build.defines=-DBOARD_HAS_PSRAM -mfix-esp32-psram-cache-issue
esp32.menu.PSRAM.enabled.build.defines=-DBOARD_HAS_PSRAM
```
