ESP8266 Monitor app
===================

First try at ESP8266 programming.

Notes to future self:
 - `esptool` and `esptool.py` are two completely different pieces of software.
 - Back then I found it rather clean to store SDK/Toolchain in some path other
   than `/opt/Espressif`, and put `export {XTENSA_TOOLS_ROOT,SDK_BASE,ESPTOOL,ESPPORT,FW_TOOL}`
   into my environment.
 - Following links may be considered friendly:
    - https://github.com/esp8266/esp8266-wiki/wiki/Toolchain
    - http://bbs.espressif.com/ (http://bbs.espressif.com/viewforum.php?f=5 in
      particular)
    - https://github.com/3s1d/esp_prog (oh, and, by the way, that was my first
      idea after getting my module, but had no time to play with it for a couple
      of weeks... :P)
 - I somehow managed to break my ESP-01, so it fails to power up on `CH_PD`, if
   not pushed down onto the table. Don't ask.
