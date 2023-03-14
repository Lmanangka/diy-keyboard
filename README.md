# diy-keyboard

Making and design my own keyboard from scratch

## Design and Components

### Front View Components

![Front view](https://github.com/Lmanangka/diy-keyboard/blob/main/img/diy-keyboard-front-view.png?raw=true)

- Switch Cherry MX
- Cherry MX Stabilizer(PCB mount stabs)

### Back View Components

![Back view](https://github.com/Lmanangka/diy-keyboard/blob/main/img/diy-keyboard-back-view.png?raw=true)
![Diodes view](https://github.com/Lmanangka/diy-keyboard/blob/main/img/diy-keyboard-diodes-view.png?raw=true)

- Diode 1N4148W

### MCU View Components

![MCU view](https://github.com/Lmanangka/diy-keyboard/blob/main/img/diy-keyboard-MCU-view.png?raw=true)

- U2 MCU ATmega32U4-AU
- Y1 Crystal oscilator 16MHz
- SW69 Reset Switch SKQG
- C1-C2 Capacitor 22pF
- C3-C7 Capacitor 0.1uF
- C8 Capacitor 10uF
- R3, R6 Resistor 10K Ohm
- R4-R5 Resistor 22 Ohm
- J1 AVR-ISP Connector

### USB-Type-C View Components

![USB view](https://github.com/Lmanangka/diy-keyboard/blob/main/img/diy-keyboard-USB-Type-C-view.png?raw=true)

- USB Type C
- FB1 Ferrite Bead
- R1-R2 Resistor 5.1K Ohm
- F1 PTC Fuse 500mA
- U1 PRTR5V0U2X

## Footprints Source

- [Switch and stabilizer](https://github.com/perigoso/keyswitch-kicad-library)
- [USB Type C](https://github.com/ai03-2725/Type-C.pretty)

## References And Credit

- [Designing a keyboard from scratch](https://www.masterzen.fr/2020/05/03/designing-a-keyboard-part-1)(mostly I used this as guide)
- [PCB Designer Guide](https://wiki.ai03.com/books/pcb-design/chapter/pcb-designer-guide)(starting point)
- [keyboard-pcb-guide](https://github.com/ruiqimao/keyboard-pcb-guide)(for reference)

