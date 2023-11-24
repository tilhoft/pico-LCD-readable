# pico-LCD-readable
## Readable font size with framebuffer on Waveshare 1.14 PicoLCD
Waveshare 1.14 PicoLCD (and most of the displays) use Framebuf Library and the documentation declares that 8x8 is the only font size available. In my opinion that is not comfortable to read, and the result is lame.

I am aware that there is a simpler solution for bigger font: https://github.com/dhargopala/pico-custom-font

But that is even better to use any font type that we want, gives the nice smooth touch to any DIY project.

Based on https://github.com/JPFrancoia/esp32_devkit_waveshare_eink_screen

Used the https://github.com/peterhinch/micropython-font-to-py/ tool to generate the console35.py font
![picolcd](https://github.com/tilhoft/pico-LCD-readable/assets/12233613/f9ecbb6a-8fd7-4f55-941a-5f70d3f4936b)
