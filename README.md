# ORCA STLINK micro debug tool

Ultra small and low cost STM debugger PCB footprint and programmer PCB. 

## PCB footprint for Fusion 360 

The footprint uses an offset design to ensure you can't connected in reverse. The end pads are through hole pads to act as registration points that the pogo pins align too to keep the profile as small as possible. 

![Screenshot 2025-05-20 134302](https://github.com/user-attachments/assets/531bab43-9d1d-4de6-a8a3-b961844df507)

## Programmer PCB boards and Peg

![Screenshot 2025-05-20 134031](https://github.com/user-attachments/assets/5c26266a-ee91-44c1-94a9-de8c51d97203)

![Screenshot 2025-05-20 134202](https://github.com/user-attachments/assets/07ed76ee-7de9-4ba7-92e0-51fcca13b8b5)

You can find the peg for programming of Aliexpress. This comes disassembled, so you can easily replace the board with the ORCA STLINK micro debug tool PCBs and then connect to your STLINK debugger to program your board.

![image](https://github.com/user-attachments/assets/611b3086-da45-4993-9a36-0a9a838627de)

You will also need to buy a header for your STLINK programmer. This is a 14 pin header, with a 1.27mm pitch. I used one like this:

<img width="772" height="421" alt="image" src="https://github.com/user-attachments/assets/344395d6-9475-4b33-a5fc-c332060842d0" />

Alterantively, I've broken our all the STLINK header pins with large 1mm header pins, so you can connect using easily sources 2.54mm header pins, or you can directly solder wires to the pads.

## PCB Design guide instructions

1. Make sure the pads are accessible with the programmer on your PCB design. The component should be near the side of your board, so it can be easily clipped. Ideally make sure no PCB parts obstruct the clip as it's moved into place, as your pogo pins on the programmer could scratch against the components on the board. Always have the peg open all the way when placing the programmer, so the pogo pins do not scratch the PCB.

2. You also need to consider the opposite side of the PCB, as the peg will press against this side of the board to hold the programmer in place. Don't place fragile parts in either areas to prevent damage.

## Programming and debugging

I use a STLINK-V3MINIE. These cost ~$20AU from Digikey to purchase. They incredible value, and make programming with STM32 chips really easy using Zephyr RTOS or Arduino.

<img width="640" height="640" alt="image" src="https://github.com/user-attachments/assets/2ab528b9-868c-4804-aca0-aee94fb0fb52" />

## Send some love if you found this helpful

This is completely open source to help out other engineers and tinkers. Enjoy :heart:

If you found it useful though and making bank, feel free to send me some coffees so I can keep making stuff open source!

<a href="https://www.buymeacoffee.com/orcamick" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

