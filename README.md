# Resources for the eGenix Talk "Programming hardware displays the easy way - using MicroPython and LVGL"

## Abstract

The world of embedded hardware devices is often considered difficult and having a steep learning curve. MicroPython has changed this for the better and now you no longer have to drop to C to implement your ideas on microcontrollers and dedicated hardware.

In this talk, we will explore the world of visualizing data using a nifty device based on the ESP32 microcontroller and a TFT display - better known under the name Cheap Yellow Display (CYD) - with the aim of creating a hardware conference talk timer.

The implementation is done in MicroPython and uses the high  quality open source embedded graphics library LVGL, the basis of many commercial devices with displays and smart watches, for beautiful graphics.

I’ll show the tooling needed to get started, useful resources, demo the application and discuss some of the pitfalls found along the way.

## Resources

- [MicroPython](https://micropython.org/)
- [CYD](https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display)
- [LVGL](https://lvgl.io/)
- [lv_micropython firmware](https://github.com/lvgl/lv_micropython) (broken for the CYD - as of May 2025)
- [lvgl_micropython firmware](https://github.com/lvgl/lv_micropython) (new development, but not quite there yet)
- [LVGL + MicroPython Firmware](https://stefan.box2code.de/2023/11/18/esp32-grafik-mit-lvgl-und-micropython/) (the blog is in German, but it provides working lv_micropython firmware downloads)

## Conference and Events

This talk was or will be held at the following events:
- [PyCon Italia 2025](https://2025.pycon.it/en/event/programming-hardware-displays-the-easy-way-using-micropython-and-lvgl) ([Slides as PDF](https://downloads.egenix.com/python/PyCon-Italia-2025-Talk-Programming-Hardware-Displays.pdf))
- [EuroPython 2025](https://ep2025.europython.eu/session/programming-hardware-displays-the-easy-way-using-micropython-and-lvgl) (Slides will be available shortly before the event)

The slides are released under the same license as the other files in this directory (Apache2 license).

## Contact

For inquiries related to the talk, please write to info@egenix.com or contact Marc-André Lemburg at mal@egenix.com.
