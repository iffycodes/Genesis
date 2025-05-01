# Genesis
Genesis Board design

## Change history

- Removed Stemma QT connectors. Left second LDO (AP2112-3.3). It looks to only be powering the neopixel on GPIO0. Need to figure out if I can just use the main one.
- Removed voltage divider used for LiPo monitoring. Provided A13_I35 that went to I35 on the ESP.
- Removed LiPo charging circuit. VBUS is now only supplied by USB-C connector. Removed DMG3415U transistor in upper left of Page 2. Removed JST battery connector.
- Removed extra reset switches.
- Add initial annotation.
- Rename +3V3 net on RTC page to match 3.3V global net name.
- Rename MISO nets on Ethernet page so global MISO net can go to buffer
- Remove second LDO. Power Neopixel from main regulator.
