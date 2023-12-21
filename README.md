# dlt-one-draw
[Damn Linux Tablet one](https://github.com/timonsku/Damn-Linux-Tablet-PCB-Design-Files/)-inspired tablet. Project goal is to make a tablet that is better than reMarkabel on three things:
* Drawing for work puropses - Draw to communicate
* Getiting those drawings into the rest of your workflow - Figma, Powerpoint etc.
* Endless canvas - If you want to draw more, you can do that. Not restricted to a physical format.

## Prototype

### Software to be used:

* Some stripped down Linux server distribution. Ubuntu/Debian
* [X11 to run one application](https://raspberrypi.stackexchange.com/questions/11866/how-can-i-start-x11-only-for-a-single-application) (a browser) with graphical UI
* Browser: Chromium or Firefox
* [tldraw](https://github.com/tldraw/tldraw) - A tiny little drawing app

### Hardware

For a working prototype

* 7" touch-screen
* Raspberry PI Zero 2 W
* Mounting plate [from aluminum, laser cut at Ponoko](https://www.ponoko.com/materials?materialTypes=metal)
* Screen frame and backplate [from acrylic or wood, laser cut at Ponoko](https://www.ponoko.com/materials?materialTypes=plastic,wood) and glued/dissolved together.

### Progress

* Raspbian server version installed on Raspberry Pi Zero W
* Connected to Manga Screen 2
* Getting some graphical interface to show on the screen with X11.

Next step is to get the screen up and running properly, then get the touch input to work.

| Screen and Raspberry Pi connected | Raspbian installed and running | Firefox showing on screen |
|---|---|---|
| ![Screen and Raspberry Pi connected](https://raw.githubusercontent.com/eklem/dlt-one-draw/trunk/IMG_20231219_182528.jpg) | ![Raspbian installed and running](https://github.com/eklem/dlt-one-draw/blob/trunk/IMG_20231219_182814.jpg?raw=true) | ![Firefox showing on screen](https://github.com/eklem/dlt-one-draw/blob/trunk/IMG_20231220_193450.jpg?raw=true) | 

## Upgrades for a second prototype

* Built in battery
* BMS / UPS for sleep/power/charge etc. - [PiJuice Zero](https://uk.pi-supply.com/products/pijuice-zero) seems to be able to do the work needed.
* Larger screen

