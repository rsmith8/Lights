# Lights
## 1. Hardware
* [Light Strands][Strand]
* [Power Supply][power] 
* [Arduino Nano][nano] 
* Raspberry Pi and equipment
* Wires, 470 ohm resistor, 1000 uF Capacitor, and heat shrink

[strand]:   https://www.amazon.com/gp/product/B014QZNC1S/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1
[power]:    https://www.amazon.com/gp/product/B01LXN7MN3/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1
[nano]:     https://www.amazon.com/gp/product/B0713XK923/ref=ppx_yo_dt_b_asin_title_o08_s01?ie=UTF8&psc=1
[ada]:      https://learn.adafruit.com/adafruit-neopixel-uberguide/basic-connections
[library]:  https://github.com/adafruit/Adafruit_NeoPixel/blob/master/README.md
[arduino]:  https://downloads.arduino.cc/arduino-1.8.16-linuxarm.tar.xz
[aiy]:      https://aiyprojects.withgoogle.com/voice-v1/#assembly-guide--get-the-voice-kit-system-image

## 2. Hardware Setup
* [Assemble power filter and connect to arduino][ada]
![PXL_20211106_170610332](https://user-images.githubusercontent.com/4064492/140619313-5f5bcc7c-cb24-4e38-aea7-a4d8cb5275af.jpg)
* Attach filter and contoll to lights being carefull to align polarity
![PXL_20211106_170553406](https://user-images.githubusercontent.com/4064492/140619410-cb33d329-4d0f-4f5e-8866-9e0698174828.jpg)
* Connect wires to the power supply screw terminals making sure to align the polarity 
* Connect nano via USB to the Pi

## 3. Software Setup
* Setup the Pi to connect remotely
* [Install arduino IDE][arduino]
* [Add Adafruit NeoPixel Library][library]
* Open strandtest example from the custom libraries and upload

## 4. Install
* Plug in power supply
* Tweak software and repeat...

## 5. To do
* Add [audio commands][aiy]
* Play music
* Add choreography orchestration
* Install outside

