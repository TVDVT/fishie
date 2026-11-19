# Fishie 
<img width="1198" height="955" alt="fishieflat" src="https://github.com/user-attachments/assets/dacae339-b230-40ae-a710-b80af16310cc" />
<img width="1198" height="955" alt="image" src="https://github.com/user-attachments/assets/b8f3a776-356d-4992-90bf-091be138e394" />


Fishie is a tiny motion-controlled digital pet: basically a desktop Tamagotchi with minimal gameplay buttons. Instead of pressing controls, you interact with it by physically moving the board.

## What it is
Fishie is designed to sit on your desk, show its personality on a small display, and react to how you handle it. Tilting, moving, and otherwise checking in on your pet are meant to be part of the experience.

The screen contains a little koi fish that swims freely from left to right. You can pet it, feed it and play with it using both the key switches and a tilting mechanism. As you play with it, its energy decreases, making him sleepy. Thankfully, there is an option to let the fishie sleep :D. Its love also increases as you play with him and pet him so keep him busy!

The board includes a microcontroller, display, motion sensor, and environmental sensor in a compact PCB design. It is USB powered and built around beginner-friendly through-hole soldering for the add-on components.

## Why?

Instead of doing a Starbie guide from Half life (but submitting it only to Fabricate), I wanted to make it my own and therefore decided to have a little fish in a fish bowl because out of all the pets, fishies are the most low maintenance but very beautiful, especially koi fishies! I do have four fish in a fish tank at home  but having one right on your desk without having the risk of water spilling on all your electronics is a lot better, and it takes less space too!

## Project status

The PCB design, renders, and an Arduino starter firmware are included here. The default program is a koi fish with a tilt-controlled radial menu, hidden stats, and a shake reaction.

## Software

[`Firmware/`](Firmware/) contains one self-contained Arduino IDE sketch for the XIAO ESP32-C3. Builders customize pins, menu actions, starting values, and motion settings together at the top of the sketch. 

## Repository contents

- `PCB/` - KiCad source files and fabrication exports
- `Renders/` - front and back PCB renders
- `Firmware/` - Arduino IDE starter sketch

# Schematic and PCB
<img width="425" height="329" alt="Screenshot 2026-11-04 075435" src="https://github.com/user-attachments/assets/19811303-4547-4adb-be78-855be9a9d4c0" />
<img width="460" height="283" alt="image" src="https://github.com/user-attachments/assets/b79e7816-b1f7-46f2-9c32-832ba062809d" />


# Fishie – bill of materials

| Part | Type | Quantity | Unit Price (USD) | Line Total (USD) | Vendor | Funding | Notes |
|------|------|----------|------------------|------------------|--------|---------|-------|
| XIAO ESP32-C3 | Part | 1 | - | $7.06 | AliExpress | Grant | |
| 10k Resistor | Part | 1 | - | $1.73 | AliExpress | Grant | |
| PCB | PCB | 1 | - | $1.33 | JLCPCB | Grant | |
| DHT11 | Part | 1 | - | $1.92 | AliExpress | Grant | |
| MPU6050 | Part | 1 | - | $1.99 | AliExpress | Grant | |
| 0.96" OLED Display | Part | 1 | - | $1.99 | AliExpress | Grant | |
| MX Switches | Part | 2 | $0.23 | $0.46 | AliExpress | Already Own | |
| Keycaps | Part | 2 | $0.20 | $0.40 | AliExpress | Already Own | Own |
| 3D Printed Case | 3D Printed | 1 | - | - | - | Grant | |
| Shipping | Shipping | 1 | - | $0.00 | - | Grant | |

### Cost Summary

| Category | Total (USD) |
|----------|------------:|
| Total Project Cost | $16.88 |
| Grant Total Requested | $16.02 |
