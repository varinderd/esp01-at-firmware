# ESP01 AT Firmware
A collection of AT firmware for ESP-01 module with 1MB flash.

# Flash using the esptool
```bash
esptool.py -p <UART-PORT> -b 115200 write_flash 0x0 esp01-xxxxxx.bin
```

# Where are these from?
Older versions of the firmware fragments merged together to make life easier!
