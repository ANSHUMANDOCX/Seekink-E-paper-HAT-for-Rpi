# Seekink-E-paper-HAT-for-Rpi
This a HAT for a epaper display for SEEKINK displays with raspberry pi Also can be used with any oher MCU using the 9 in connector. It supports multiple Displays of almost every Size

## Parts
- Raspberry Pi Zero 2 W
- 3.5 inch Epaper Display

## Plan
I needed a HAT that could be used with a Cheap Epaper dispaly paired with a raspberry pi. I found one on LCSC but it didnt have a HAT of that wa 100% compatible with it. 
So, i took reference from existing HATs and the Datasheet of the Epaper Display and made my own that could be attatched on top of raspberry pi WH.
I also added a 9 pin connector and a Voltage Level shifter so that i can connect it to most of the microcontrollers.
## PCB
![image](https://github.com/user-attachments/assets/a9ba6f21-2f37-46eb-a6db-7d9b7c5b8f97)
![image](https://github.com/user-attachments/assets/229bf69e-b5ce-4472-ae0a-789390241e0d)
![image](https://github.com/user-attachments/assets/315289d6-3fa9-4e33-ac28-fac569770b58)

## BOM
| S.No | Product Code | Description                       | Quantity | Total Price | Supplier | Category            |
|------|--------------|-----------------------------------|----------|-------------|----------|---------------------|
| 1    | C500051      | SK-3296S-01-L2 Slide Switch       | 5        | $0.39       | LCSC     | Passive Components  |
| 2    | C5224028     | PM2.54-1*9 Female Header (1x9P)   | 5        | $0.52       | LCSC     | Connectors          |
| 3    | C2977589     | 2.54-2*20 Female Header (2x20P)   | 5        | $0.97       | LCSC     | Connectors          |
| 4    | C53406       | TXB0108PWR Level Shifter          | 5        | $1.25       | LCSC     | ICs                 |
| 5    | C41416467    | SEEKINK E037A49 E-Ink Display     | 1        | $7.22       | LCSC     | Display             |
| 6    | —            | 0603 Resistors (47kΩ + 3Ω total)  | —        | $0.25       | LCSC     | Passive Components  |
|      |              | **Total**                         |          |10.77|          |                     |
|||Raspberry Pi zero 2 W+ adapters||21|Silverline|||
|||PCB+ Shipping||12|JLCPCB|||
