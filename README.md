# RPI-tft-clock

Raspberry Pi Clock

I bought a cheap GPIO TFT screen, not knowing what a pain it would be. This small screen had drivers from 2016, 9 years old when I bought it. Due to the lack of drivers, I just kept it in a drawer. I finally got it to work with a Pi 4B after finding a driver for these cheap screens. It worked, but looked terrible, from colors to refresh rate to viewing angles. I then got it to work with the Pi Zero and decided to make a clock. I used Python and PIL to make a basic clock with a background that can be uploaded via SCP.

the background.jpg must be in the same folder as the program

```git clone https://github.com/goodtft/LCD-show.git```
```chmod -R 755 LCD-show```
```cd LCD-show/```
```sudo ./LCD35-show```

the driver I used for the tft screen

I built a stand for it with lego

<img width="1024" height="768" alt="EE441B53-1C4C-4F8F-BF9A-BC84E8F5E5CC_1_105_c" src="https://github.com/user-attachments/assets/5ad418c5-f410-44d1-83d0-fe4b79c341d4" />

