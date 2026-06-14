# Working ESPHome configuration for Waveshare ESP32 S3 LCD 1.54 Touch

I built a working full ESPHome configuration for Waveshare ESP32-S3-Touch-LCD-1.54 https://docs.waveshare.com/ESP32-S3-Touch-LCD-1.54 (mine is SKU 33869, with touch and battery, but it's matter of commenting some lines for other variant SKUs)

this inexpensive device (20 €) you con buy on aliexpress or on the product website is very usefull as "mini-satellite" for Home Assistant, has:
- good wifi
- 3 configurable very fast button
- 240x240 display fully configurable with LGVL, with also touch and swipe capability
- mini speaker, not good for music, not super loud, but ok for clear test-to-speech messages and alert sounds
- microphone (i didn't test)
- accelerometer (i didn't test)
- sd card (i didn't test)
- battery (hot swappable from cable power, but I didn't test the duration)

I built the conf with claude code help in about a day. I fixed a lot of small issues like removing sound pop in, missing pin documentation, correct screen rotation, auto display off, etc.

The device now is fully usable for any of my use cases in HA without any issues.

Enjoy!

PS: don't forget to set the api key and ota password

PPS: I don't plan to maintain it
