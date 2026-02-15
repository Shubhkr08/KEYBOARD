# KEYBOARD
I started with picking up Raspberry Pico as out main microcontroller and this would be a 60 % layout Keyboard with 2 rotor encoders.
The rotor encoders will be use to control Brightness and Volume and the switch in those 2 encoders will act as a custom key to take screenshot and to delete.
I also did the schematic of the keyboard, I added the stabilizers to the switches which were longer then 1.75U.
The Keyboard uses a matrix grid so i need only a few gpio pins for the whole keyboard to work.
## Features

- Base on Raspberry pico
- Has 61 keys ( 60% Keyboard Matrix)
- Has 2 Rotor Encoder
  ### Schematic
  <img width="1309" height="939" alt="Screenshot (97)" src="https://github.com/user-attachments/assets/f3ae7811-5523-4442-93c6-677eab70dc50" /><br>
  ###  PCB Design
<img width="1215" height="424" alt="Screenshot (99)" src="https://github.com/user-attachments/assets/ffa85bf6-a7ba-4473-91e8-69f158677a0a" /><br>
### 3D Design
<img width="1246" height="367" alt="Screenshot (101)" src="https://github.com/user-attachments/assets/e43c7580-b26f-4b8a-88a6-54985101769f" /><br>
<img width="1271" height="388" alt="Screenshot (100)" src="https://github.com/user-attachments/assets/10dd9fc8-cdd3-4b29-afed-8b2d7d05ad79" /><br>

- ## Bill of Materials (BOM)

| Item | Quantity | Description | Unit Price (USD) | Link |
|-----:|---------:|-------------|------------------:|------|
| Cherry MX Switch (MX2A-HC1B) | 61 | Mechanical key switch | 1.95 | https://www.digikey.in/en/products/detail/cherry-americas-llc/MX2A-HC1B/21738427 |
| 1N4148 Diode | 61 | Switching diode for key matrix | 0.041 | https://www.digikey.in/en/products/detail/onsemi/1N4148TR/458811 |
| Raspberry Pi Pico (RP2040) | 1 | Main microcontroller board | 5.00 | https://www.digikey.in/en/products/detail/raspberry-pi/SC0917/16608257 |
| Keycaps Set | 1 | Backlit mechanical keyboard keycaps | 38.68 | https://www.amazon.in/Keycaps-Backlit-Mechanical-Keyboard-Switches/dp/B08R5YPYCD |
| PCB + Shipping (JLCPCB) | 1 | PCB fabrication and shipping | 29.51 | https://jlcpcb.com |
| Stabalizers | 5 pair  | I have them | 0 | ---- |
| M3 screws and heatset | 8  | I have them | 0 | ---- |

**Estimated Total Hardware Cost:** **USD 194.64**

## Hardware
- Raspberry Pico 
- Cherry MX compatible Switches
- Diode
- 2 layer PCB
- 2 Rotor Encoder

## Firmware
- It is Based on KMK and Circuit Python
