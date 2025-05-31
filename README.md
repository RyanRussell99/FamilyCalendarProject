# Family Calendar Project
An Android on Raspberry Pi 4 based touch screen device. This will be used to display a family calendar via the Google Calendars App.

## Hardware 
[Raspberry Pi 4B](https://www.amazon.com/Raspberry-Pi-Model-2GB/dp/B09TTNPB4J/ref=asc_df_B09TTNPB4J?mcid=2c5ccffa65ba37dbb16096936126bcea&tag=hyprod-20&linkCode=df0&hvadid=704452679949&hvpos=&hvnetw=g&hvrand=14562040055780680493&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9021906&hvtargid=pla-1885436594092&psc=1&hvocijid=14562040055780680493-B09TTNPB4J-&hvexpln=0)

Touch Screen Display

TBD

## Software

This implementation utilizes Lineage OS and MindTheGapps to get Android running on the Raspberry Pi 4B with Google services.

[Raspberry Pi Imager](https://www.raspberrypi.com/software/)

[LineageOS 22](https://konstakang.com/devices/rpi4/LineageOS22/)

[MindTheGapps 15](https://github.com/MindTheGapps/15.0.0-arm64/releases/tag/MindTheGapps-15.0.0-arm64-20250214_082511)

[Google Apps Installation for LineageOS](https://wiki.lineageos.org/gapps/)

On install, change the display size and text in to be the smallest in:  Settings -> Display -> Display size and text 

Display Resolution Change: Settings -> System -> Raspberry Pi Settings -> Display Resolution (Requires reboot to apply)

Enable Developer Settings: Settings -> About Tablet -> Press Build number 7 times (a pop up will say you have enabled developer mode)

Enable Wireless Debugging: Settings -> System -> Developer Options -> Wireless Debugging

Pair Wirelessly: Settings -> System -> Developer Options -> Wireless Debugging -> Pair Device with Pairing Code

[Pair ADB over WiFi](https://wiki.lineageos.org/how-to/adb-over-wifi/)



``` shell

```
