# retro_xmas_gadget
An ESP32S3 based retro gaming handheld running retro-go the open source retro-go, inspired by Megazoid's design on his [CrokPocket](https://www.hackster.io/megazoid/crokpocket-a0ff83).

## Story
This year my niece and nephew, who are 8 and 10 became more aware of what I do for a job as an Embedded Systems Engineer and enthousiastic hobbyist. Each time when there is a family gathering, they ask about 'my inventions', and share with me their ideas what I could invent next. Since they are so interested and we are hosting Christmas this year, I wanted to share a Christmas activity where we can assemble an invention of their own, showing them what electronics can do and giving them a nice memory.

I have stumbled on Megazoid's [design](https://www.hackster.io/megazoid/crokpocket-a0ff83) of his original CrokPocket which I really liked, but I preferred a larger screen. I also had some leftover components such as a few hundred SDHD 4gb memory cards and a stack of 1900mah batteries that I could use for this design to cut cost. And I preferred the CP2102 over the CH340G, and connectors over soldering for the display. Thus the slightly larger CrokPocket XL was born.

Even though this DIY handheld doesn't compare to many linux based emulator machines that are out there, it can't compete to something that you have build yourself. And I actually find that the keypad feels more snappy, I much prefer the shorter throw and click.

## Instructions

### 1. Ordering

### 2. Soldering

### 3. Flashing

### 4. Printing

### 5. Assembly

## Bill of Materials

## Release Notes

### Changes

* Version 0.9.0
    * Initial 4-layer PCB design

* Version 1.0.0
    * Correct ESP32-S3 footprint, apply keepout area to inner layers
    * Move Screw holes to corners
    * Add Load-sharing Circuit for charging

* Version 
    * Footprint Correction for Q3
    * Change values for thermal protection resistors, R17, R23