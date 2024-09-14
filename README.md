# mai_pico_clamshell_case

A simple and concise housing case for mai_pico.

## Introduction

This project is a housing case for the project [whowechina/mai_pico](https://github.com/whowechina/mai_pico).

This project is highly depends on 3D printing and your budget, it may cost about 300 CNY for v1, about 200 CNY for v2.

There are some features if you use this housing case:

- Clamshell design for easy to open and access.

- Comfortable front side look with no screws.

- Make the most of what's left after making mai_pico.

- Easy to take and set the background of the top frame.

## Disclaimer

This project has no affiliation to S... company.

I'm new to model design, I hope to let me know if some of the designs will cause problems.

I'm not sure if there is better way to make this housing case out. If there is, feel free to tell me via an issue.

3D print can be rough, I won't answer for any issues caused by the quality of 3D printing.

It is not allowed to make too much profit from this project.

## How to build

### BOM (Bill of material)

*All dimensions are in millimeters.*

|Name|Specs|Count|Notes|
|----|-----|-----|-----|
|Soldering iron|-|1|For melting nuts (v2)|
|Hot melt insert nuts|M3×4×5(inner & outer diameter, length)|17|Provide mounting holes for screws (v2)<br>It is ok to change to M2 spec if you left some screws after making mai_pico|
|Screws|M3×4|17|To assemble the back-board and border(v2)<br>It is ok to use the screws that are left after making mai_pico|
|Steel shafts|⌀2×4|4|Shaft for clamshell & head-cover fixing|
|Adhesive tape|-|1|To stick the screen tray|

### For v1

**(This version may cost more, and it is recommended to use v2 instead.)**

**This model has not been tested yet, Please use it with caution.**

1. Download all the files in `/Production/` folder.

2. Print `front-panel.step` `back-panel.step` using a 3D printer (make sure the printer can print up to 410mm). And seach acrylic customization on a e-commerce platform, send the file `head-cover.step` and ask if they can make.
  - In addition, you can design a border background for the head screen. I made a diagram `border-size.png` to show you the size of the border.

4. Cover the front panel, and you can see some grooves on you left side. Put a steel shaft in the wider groove then push it through the round hole. Another groove do so.

5. Make sure to disconnect the zebra cable from ITO coated glass and the IO PCB (you can simply separate them with a hair dryer). Place your PCB on the back panel with the front side of the PCB facing up. Each hole on the PCB should be aligned with the four posts on the back panel. Then, install a screw on each hole.
  - If you also added a PN532 module, you can place it in the reserved slot blow.

6. On the side of front panel you can find a gap. Push your glass into the gap, and you will see the gold finger on the glass appeared in the groove on the other side, now you can stick the zebra cable again.

7. On the front panel you can find some bumps surround the circle, they fits your button ring. Apply some double-sided tapes to appropriate position around the circle, and put the leading wires into the hole on the left. Tear off the double-sided adhesive stickers, put the button ring in place, and organize the wires in the back.

8. On the upper side of the front panel, align the bottom of the acrylic to the groove and put it in, then close the upper part and fix it with steel shafts on the back.

### For v2

1. Download all the files in `/Production/` folder.

2. Search acrylic customization on a e-commerce platform, send file `back-board.step`, `head-cover.step` and ask if they can make. Print files `border-upper.step`, `border-lower.step` and `front-panel.step` using a 3D printer (you can also ask some e-shop if they can print a larger size model).

3. To be continue

## License

![[License](https://creativecommons.org/licenses/by-nc-sa/4.0/)](https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-nc-sa.png)

This project is under a [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.