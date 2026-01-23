as with our attempts at he wowehina pop'n pcb we developed what we wanted based on the problems we had - our own design would eventually do away with the additional USB port and the side facing LEDs. our class project is working on changing up some parts of gp2040-ce firmware to make the web interface relevant and straight forward just for this controller and the shape being somewhat different for lighting effects to bring our yuancon SDVXlite (with the typos) homage to life. to prototype the change to a rp2040nano and being nowhere near having the top design finished we knocked this up to replace our poorly looking PCBs from the SpeedyPotato , repeated soldering, bad LEDs, clumsy repairs, clumsy playing put them to the test - this lines up so we could reuse our top plates. As it is the traces are like a drunk octopus but it works and meets the different needs we had. the rp2040zero is mounted underneath but faces upright so the top of it (with the bootsel button etc) is facing inwward to the controller, using header pins through the holes makes it very rigid and over-keen-child friendly. no repairs needed yet and £5 cheaper per device in parts

<img width="2160" height="1349" alt="3D_Pocket-SDVX-Pico_2026-01-23" src="https://github.com/user-attachments/assets/853a3255-59d2-421c-a2d7-2f79473e891d" />



same as the other projects, this will get tidied up whenever time allows, gpio pins are different so adding modified version of SP's firmwware that works but it's not proper as this LED layout is temporary so i'e not touvched that, they light up and look pretty still.

![my-yuancon-sdvx-lite-3-review-pros-cons-and-the-rest-v0-5wwrzyfssgz91 (2)](https://github.com/user-attachments/assets/8da65d66-97c4-4c2b-89ba-85f4a682ff48)


# Pocket-SDVX-Pico-v4
Pocket SDVX Pico v4 source files, production files, and documentation

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.  中国人，我在看你们。

![Pocket SDVX Pico v4](pocket_sdvx_pico_top_c.jpg)

Although I won't be selling this particular version anymore, I have plans to sell updated designs soon.  Join the discord for discussion and support! https://discord.gg/MmuKd73XbY . I also now have a storefront! https://www.speedylabs.us/

## Parts Required:
- JLCPCB parts (Boards are 180 mm*100 mm, white PCB color, remove order number[specify a location]):
    - 1x Pocket-SDVX-Pico-Plate-v4-2 (MOQ 5)
    - 1x Pocket-SDVX-Pico-v4-3 + SMT Assembly (MOQ 5)
        - SMT Assemble the top side.  There should be 9 unique parts.
- McMaster parts:
    - 4x Feet - 8884T13
    - 4x M3 Lock Nut - 90576A102
    - 4x M3x12 Screw - 92095A183 
    - 4x No.6 1/8" Nylon Spacer - 94639A507 
- Mouser parts:
    - 2x 2U Stabilizer - 540-G99-0224
    - 2x Encoder - PEC16-4015F-N0024
- 1x Raspberry Pi Pico
- XDA Keycap Set https://www.speedylabs.us/product/pocket-sdvx-keycaps/
    - 1x 1u, 4x 1.5u, 2x 2u
- 2x 22mm Knob https://www.speedylabs.us/product/pocket-sdvx-aluminum-knob/
- 7x Gateron Yellow Switches (GATERON KS-9 or any switch with LED cutout)
- 7x Gateron Hotswap Sockets
- 1x 3D printed case, White PETG https://www.speedylabs.us/product/pocket-sdvx-pico-case/

[Pocket SDVX Pico v4 Quick Start Guide](https://docs.google.com/document/d/1lTzADQI5E5vRpHBv-0IfLbDSh2zEKCUAdh5BqFhex2I/edit?usp=sharing)  
[Kit Assembly Guide](https://docs.google.com/document/d/1bsWk7fmLKUGv5YgQknoNQcy0RX3fi5gCZRvfOJAa-P0/)

## Addendum
As promised many months ago, Speedy Labs' most popular product is now open sourced.  Pocket-SDVX-Pico v4 is my second PCB, and therefore everything's a little bit sloppy.  Nevertheless, everything here is functional and has been self-learned online along with the help of the community.  Thanks for all the support!

FYI I should probably let everyone know the most common defects I've received:
- RGB LEDs dead or not soldered properly
- Extra Aux Button wobbly/non-functional/misaligned
- Smudged Silkscreen

There's probably a 5% chance of this happening according to my statistics.  Nothing you can do about it aside from repairing it yourself.
