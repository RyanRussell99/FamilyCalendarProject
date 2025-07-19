# Family Calendar Project
An Android on Raspberry Pi 4 based touch screen device. This will be used to display a family calendar via the Google Calendars App.

## Hardware 
[Raspberry Pi 4B](https://www.amazon.com/Raspberry-Pi-Model-2GB/dp/B09TTNPB4J/ref=asc_df_B09TTNPB4J?mcid=2c5ccffa65ba37dbb16096936126bcea&tag=hyprod-20&linkCode=df0&hvadid=704452679949&hvpos=&hvnetw=g&hvrand=14562040055780680493&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9021906&hvtargid=pla-1885436594092&psc=1&hvocijid=14562040055780680493-B09TTNPB4J-&hvexpln=0)

[Touch Screen Display](https://www.amazon.com/dp/B0DD6HK35V?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)

[Micro HDMI to HDMI](https://www.amazon.com/dp/B06WWQ7KLV?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)

[USB-C 180 deg adapter](https://www.amazon.com/KADO-Charging-Extender-Converter-Portable/dp/B0D3VPXDY7/ref=sr_1_1_sspa?crid=8JBX7WZQB564&dib=eyJ2IjoiMSJ9.M-kkbq2u0Thk63UDlQFGymK_gWVKOsde6YHPPiRfo1vey9Ma5xrx1Uk27t5ylGkqQ-G57SdKMmxZ7L4YZ3bKiHbynVTg5JeicTPf9DOEl_06ONe9Z8fjmfMczV5fBWXAcGeLf0boSx39324FGHjGu1m5p06DEZV_y1VM85qeUCXUKeOZ-dc9eyb2JP8o-5woZwn-TiFbM0Moc_nzdd6-nDiESR8BZZ-vC0_N4MpoNTSEOWjbPG6urDH7AEaGOlcLUWql0xaHfLvsdSVTcY7YEVRFwgXKvDwjalDMsvTxJPo.BGWHvVsQpMCWK_xbjki_wGHRhvhfp-_vIBFcxfbfJNI&dib_tag=se&keywords=usb%2Bc%2B180%2Bdegree%2Badapter&qid=1752946254&s=electronics&sprefix=usb%2Bc%2B180%2Bde%2Celectronics%2C119&sr=1-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)

[HDMI 180 deg adapter](https://www.amazon.com/dp/B0CC8RL25Z?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)

[USB-C Cable and Wall Brick - A lot of options here, not just this one](https://www.amazon.com/Charger-2-Pack-Charging-Samsung-Galaxy/dp/B08G4GRQYV/ref=sr_1_20?crid=1OVRT49L1VZ8H&dib=eyJ2IjoiMSJ9.WS0BOAPIWv2y6IWeN57rVhb2aqh2ENhjyod6fkOSg9EgQ-HTCH7WUIYpL_KStkfkBkFAFbO4iQfG-hB2e4RpXVU7x3XWoF7tiprQREV-qMrtZeVexYFfPPcLpZvCOslzvFdPl7iQaIzGz9a60Nb0S6hM8OPDBh4Y-NPqi72KggUQFYaykJmLszte-lSXTkIkWyEZqGU89aBm2Ty0MBwlGT3SnUyweyb0dvHY0_By05NtaeKzQKldlAgN5qHIrJmFsV2ZOYEaw-e7xeiza8PCaR63TGevhLPCjZIx10_OAeE.ihNFUHivVLb4sFu2SLOGlXEAw7R52LMESKxAdYFND5E&dib_tag=se&keywords=USB%2Bc%2Bcharger&qid=1752946323&s=electronics&sprefix=usb%2Bc%2Bcharger%2Celectronics%2C131&sr=1-20&th=1)

## Startup to Google Calendar in Chromium




## Android Software (tried and did not work well)

This method was ultimately abandoned as the OS was too slow for the Pi 4. The alternative seemed to be a better fit for the Pi 4.

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
