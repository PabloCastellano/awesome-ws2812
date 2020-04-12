# Awesome ws2812

A curated list of awesome resources for ws281x LED strips and matrices. You usually control these devices using ESP8266 and ESP32 chips.

**NOTE: This is a WIP list that I started since I could not find any.**

**If you have an awesome project that is not listed here yet, your Pull Request is very welcome!**

## What is ws2812

The ws2812 is an intelligent control LED light source, with the control circuit and RGB chip integrated directly into a 5050 RGB LED.

Some features:

* The control circuit and the LED share the only power source.
* Built-in electric reset circuit and power lost reset circuit.
* Each pixel of the three primary color can achieve 256 brightness display, completed 16777216 color full color display, and scan frequency not less than 400Hz/s.
* Cascading port transmission signal by single line.

## Contents

### Libraries

LED strips

* [Adafruit NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel) - Arduino library for controlling single-wire LED pixels (NeoPixel, WS2812, etc.)
* [blynk](https://github.com/blynkkk/blynk-library) - Blynk library for embedded hardware.
* [FastLED](https://github.com/FastLED/FastLED) - Library for colored LED animation on Arduino
* [ledcat](https://github.com/polyfloyd/ledcat) - Simple utility that aims to provide a standard interface for driving LED-strips and such.
* [NeoPixelBus](https://github.com/Makuna/NeoPixelBus) - Adafruit enhanced NeoPixel support library.
* [WS2812FX](https://github.com/kitesurfer1404/WS2812FX) - Drop-in replacement for the Adafruit NeoPixel library with additional features.
* [raspi_ws2812](https://github.com/UrielGuy/raspi_ws2812) - A kernel module able to run as many WS2812 strips as there are GPIO pins on Raspberry Pi Zero.
* [rpi_ws281x](https://github.com/jgarff/rpi_ws281x) - Userspace Raspberry Pi PWM library for WS281X LEDs.

LED matrices

* [Adafruit NeoMatrix](https://github.com/adafruit/Adafruit_NeoMatrix) - Adafruit_GFX-compatible library for NeoPixel grids.

### LED strip controllers

* ArduLED [1.0](https://github.com/kris701/ArduLED) and [2.0](https://github.com/kris701/ArduLED-2.0) - Control NeoPixels (ws2812b) easier than ever with an Arduino!
* [EspFire2012](https://github.com/krzychb/EspFire2012) - Testing of NeoPixel libraries to do fire simulation with Fire2012.
* McLighting [v2](https://github.com/toblum/McLighting) and [v3](https://github.com/FabLab-Luenen/McLighting)- The ESP8266 based multi-client lighting gadget.
* [Music LED Strip Control](https://github.com/TobKra96/music_led_strip_control) - LED strip audio visualization in real time with web interface on a Raspberry Pi.
* [Music Reactive WS2812B Arduino](https://github.com/AnshumanFauzdar/Music-Reactive-WS2812B-Arduino) - LED STRIP WS2812B reacting to music connected through your AUX 3.5mm Jack.
* [Responsive LED Control](https://github.com/doctormord/Responsive_LED_Control) - Responsive Led Control based on McLightning & Grisworld-Led-Controller with FastLED.
* [Simple LED Strip Controller](https://github.com/eighthree/Simple-LED-Strip-Controller) - ESP8266 Based LED light strip controller via a web browser.
* [xmas-tree](https://github.com/designer2k2/xmas-tree) - XMAS Tree from stacked ws2812 rings driven by a Digispark.
* [WLED](https://github.com/Aircoookie/WLED) - Control WS2812B RGB LEDs with an ESP8266 over WiFi!
* [WS2812Serial](https://github.com/PaulStoffregen/WS2812Serial) - Non-Blocking WS2812 LED Library.

### LED matrix controllers

* [FB.Light](https://github.com/bombcheck/FB.Light) - WiFi-LED-Strip-Controller with NTP-driven scrolling clock, text and other effects.
* [White Rabbit](https://github.com/jwalanta/whiterabbit) - Neopixel based XY Matrix running via Raspberry Pi to display time, weather, and news.

### Projects

* [Audio Reactive LED Matrix](https://github.com/modustrialmaker/Audio-Reactive-LED-Matrix) - Code for 16x16 LED Matrix (WS2812) that reacts to sounds detected from an electret microphone, and switches modes with a momentary push button.
* [ESP8266 NeoPixel Dashboard](https://github.com/neoxharsh/ESP8266_NeoPixel_Dashboard) - ESP8266 based Neopixel dashboard, it shows current time, can show a custom message and have upto 41 prebuild effects.
* [NeoMatrix Generator](https://github.com/cesnokov/NeoMatrix-Generator) - NeoMatrix VISIWIG graphics editor.
* [NeoPixel2048](https://github.com/peacheym/NeoPixel2048) - Implementation of the popular game '2048' built using a 4x4 NeoPixel Matrix and powered by the Arduino micro-controller.
* [LED Protest Sign Scroller](https://github.com/danasf/LEDProtestSign) - WS2812 Matrix Protest Sign.
* [Satellite tracker](https://github.com/PaulKlinger/satellite_tracker) - Project that shows satellites and space junk flying overhead.

### Videos

* [Fire2012: fire simulation for Arduino and LEDs](https://www.youtube.com/watch?v=_oVVCXOFDkw)
* [Using I2S on the ESP8266 to drive WS2812Bs](https://www.youtube.com/watch?v=6zqGwxqJQnw)

### Miscellanea

* [Best practices](https://learn.adafruit.com/adafruit-neopixel-uberguide/best-practices) to avoid damaging your NeoPixels.
