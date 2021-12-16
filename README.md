# WLED ESP32 Controller

![Alt text](./Images/IMG_7885.jpeg?raw=true "overview")

![Alt text](./Images/WLED_ESP32_Controller.png?raw=true "overview")

## Features
- 5V/GND connector for input voltage
- 4 output lines for LED data or relais
- level shifter for all 4 outputs (3.3V -> 5V )
- resistor for data lines
- support for LED strips with clock signal
- connector for microphone sensor or button input (ADC1, GND, 3.3V, IN1, GND, IN2, GND)
- connector to flash firmware with CP2104 (3.3V, TX, RX, GND)

## BOM
- 1 x WLED ESP32 Controller presoldered
    - C1, C3: 10µF 0805
    - C2: 47µF 0805
    - C4: 100nF 0805
    - R1, R2, R3, R4: 330 Ohm 0805
    - R5, R6: 10k Ohm 0805
    - SW1, SW2: SW-SMD-3.7x6.1_2P
    - U1: AMS1117-3.3 SOT-223-3
    - U2: ESP-WROOM-32
    - U3: SN74AHCT125DR
- 2 x 3-pin screw terminal (https://www.amazon.de/gp/product/B07PPRYT4X)
- 1 x 4-pin header male
- 1 x 7-pin header male

## Wiring diagram
- https://github.com/Hasenpups/WLED_ESP32_Controller_Public/blob/master/WLED_ESP32_Controller.pdf

## Software
- WLED - https://github.com/Aircoookie/WLED/releases
- Sound Reactive WLED - https://github.com/atuline/WLED/releases

## WLED configuration
- OUT1 - pin 16
- OUT2 - pin 17
- OUT3 - pin 18
- OUT4 - pin 19
- Microphone input - pin 36
- Button input 1 - pin 26
- Button input 2 - pin 27

![Alt text](./Images/Pinout.png?raw=true "overview")

## Case
- https://github.com/Hasenpups/WLED_ESP32_Controller_Public/blob/master/Case/WLED_ESP32_Controller_Case.stl
