# gpauto

./gpauto for HERO4/HERO5 (spirtitual successor to autoexec.ash/override.sh/cal.txt) on stock Firmware

## Script:

```
[your ssid pass]
gpsend XX%[number]
```

## How to load scripts:

Rename script to "gpauto" and place in the root of the SD card.

Insert SD card into the camera, remove battery, insert battery and 
power on.

DCIM MISC gpauto

## Script descriptions:

```
.
├── shutter_start = Start shooter on boot
├── wifi_ap_on = Turn WiFi APP mode on boot
├── change_wifi_settings = change GoPro Wifi SSID and password

```

## Commands available:

- WM 01 = WiFi APP mode
- WM 00 = WiFi OFF
- SH 01 = Shutter start
- PW 01 = Video mode
- PW 02 = Photo mode
