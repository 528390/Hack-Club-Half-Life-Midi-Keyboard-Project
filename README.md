Custom MIDI Keypad

What is this project?
This project is a custom MIDI keypad designed using KiCad. It is designed to be a compact MIDI controller with multiple inputs for controlling music software and MIDI parameters.

How does this project work?
The keypad uses a Seeed Studio XIAO ESP32-S3 microcontroller to control its components. Five capacitive touch keys provide inputs, while a rotary encoder, slider potentiometer, and two buttons allow for additional controls. Two RGB LEDs provide visual feedback. The controller will be programmed to respond to these inputs and send MIDI controls.

List of hardware components:

XIAO ESP32-S3 Microcontroller

Capacitive Touch Keys(5x)

Push Buttons/Switches(2x)

Rotary Encoder(1x)

Slider potentiometer(1x)

SK6812 MINI-E RGB LEDs(2x)

Custom PCB designed with KiCad

My Project Status: The schematic and PCB design are complete along with the fabrication of the PCB. The next steps are to assemble the components and program the controller. My goal is to build a working MIDI keypad and test its functions on the physical hardware.

Repository Contents:

BOM.md — Bill of materials

JOURNAL.md — Project progress and development notes

KiCad schematic and PCB design files

PCB fabrication files

PCB Images

<img width="1191" height="815" alt="schematic layout" src="https://github.com/user-attachments/assets/52cdaa36-72b5-440c-8199-2939ded1d485" />
<img width="712" height="750" alt="PCB layout" src="https://github.com/user-attachments/assets/0a777742-f62d-46ac-ad1b-2fb6052f849d" />
<img width="706" height="752" alt="wired PCB" src="https://github.com/user-attachments/assets/e866e52a-2545-4443-909a-c8fd5db8082b" />

Bill of Materials(BOM)

| Part / Material | Quantity | Unit Price | Buying Link |
|---|---|---|---|
| XIAO ESP32-S3 | 1 | $7.49 | [Seeed Studio](https://www.seeedstudio.com/XIAO-ESP32S3-p-5627.html?srsltid=AYCX9vKBiG3yXomgK8mtnrat1UVJGn21lygE4s9NAptKjhPrmF6KQD_9)|
| SK-6812 MINI-E RGB LEDs | 2 | $0.48 | [Keebio](https://keeb.io/products/sk-6812-mini-e-rgb-leds-12-pack?srsltid=AYCX9vJFJ4jl6KGsg4EfYtZQteIyzEm-eaSoc4ZBs4j6uTuhBcA0I3lI) |
| Rotary Encoder | 1 | $1.80 | [Amazon](https://www.amazon.com/WWZMDiB-Encoder-Digital-Potentiometer-Arduino/dp/B0C6Q67V97/ref=sr_1_3?dib=eyJ2IjoiMSJ9.LNLYt-5Y5_JKxN4PBXO6ok6N2GvGv9L6H8adZYaoG3IpHcUVF85ubHLPDBZCLeax6RjYacYK096S-HdAHi3qS_LSErALg9TToMeFkjRYCRhxEFakSky5QZqqECrWmz8ToKD7Vli-6_aquDh28D2qEL6v7Xyu-gHMXSvDIsI4pj5G6Oj4OSwpkdIdgmyYprPLrgmqQGw939syZ9DV2qCjEGx250yAKIQLslCpasML86Y.apdnFheyWpuC-pf7c7-vZv1--i16EvIffz9bOvJzAMI&dib_tag=se&keywords=rotary+encoder+switch&qid=1792949136&sr=8-3) |
| Potentiometer | 1 | $1.58 | [Digikey](https://www.digikey.com/en/products/detail/bourns-inc/PTA1543-2015CPB103/3781165) |
| Push Buttons | 2 | $0.93 | [Amazon](https://www.amazon.com/dp/B0B3MMMWPN?lv=shuf&channelId=500&plpRedirect=mhFallback) |
| Custom PCB | 1 | $4.00 | [PCB manufacturing](https://jlcpcb.com/) |
