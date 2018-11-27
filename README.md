# LUA_RC522
MFRC522 RFID reader/writer for the NodeMCU

This fork provides a way to initialize and poll multiple RFID readers simultaneously.

To use, call `init(pin)` with the GPIO pin that you want to read, and then call `poll(pin)` to search for a card and receive it's serial number.

Fork of RC522 RFID Reader for NodeMCU LUA By Ben Jackson

This is a port of:
https://github.com/ondryaso/pi-rc522        -> Python
https://github.com/ljos/MFRC522             -> Arduino

To be used with MFRC522 RFID reader and s50 tag (but can work with other tags) with the NodeMCU devkit V1


  
