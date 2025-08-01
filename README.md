# Seekink-E-paper-HAT-for-Rpi
This a HAT for a epaper display for SEEKINK displays with raspberry pi Also can be used with any oher MCU using the 9 in connector. It supports multiple Displays of almost every Size

## Parts
- Raspberry Pi Zero 2 W
- 3.7 inch Epaper Display

## Plan
I needed a HAT that could be used with a Cheap Epaper dispaly paired with a raspberry pi. I found one on LCSC but it didnt have a HAT of that wa 100% compatible with it. 
So, i took reference from existing HATs and the Datasheet of the Epaper Display and made my own that could be attatched on top of raspberry pi WH.
I also added a 9 pin connector and a Voltage Level shifter so that i can connect it to most of the microcontrollers.

It can be programmed using the GxEPD2 Library
## PCB
![image](https://github.com/user-attachments/assets/a9ba6f21-2f37-46eb-a6db-7d9b7c5b8f97)
![image](https://github.com/user-attachments/assets/229bf69e-b5ce-4472-ae0a-789390241e0d)
![image](https://github.com/user-attachments/assets/315289d6-3fa9-4e33-ac28-fac569770b58)

## BOM
| S.No | Product Code | Description                       | Quantity | Total Price | Supplier | Category            |LINK|
|------|--------------|-----------------------------------|----------|-------------|----------|---------------------|-------------------------------|
| 1    | C500051      | SK-3296S-01-L2 Slide Switch       | 5        | $0.39       | LCSC     | Passive Components  |https://lcsc.com/product-detail/Slide-Switches_XKB-Connection-SK-3296S-01-L2_C500051.html?s_z=n_C500051|
| 2    | C5224028     | PM2.54-1*9 Female Header (1x9P)   | 5        | $0.52       | LCSC     | Connectors          |https://lcsc.com/product-detail/Female-Headers_ZHOURI-PM2-54-1-9_C5224028.html?s_z=n_C5224028%2509|
| 3    | C2977589     | 2.54-2*20 Female Header (2x20P)   | 5        | $0.97       | LCSC     | Connectors          |https://lcsc.com/product-detail/Female-Headers_ZHOURI-2-54-2-20_C2977589.html?s_z=n_C2977589|
| 4    | C53406       | TXB0108PWR Level Shifter          | 5        | $1.25       | LCSC     | ICs                 |https://lcsc.com/product-detail/Translators-Level-Shifters_Texas-Instruments-TXB0108PWR_C53406.html?s_z=n_C53406|
| 5    | C41416467    | SEEKINK E037A49 E-Ink Display     | 1        | $7.22       | LCSC     | Display             |https://lcsc.com/product-detail/E-ink-Display_SEEKINK-E037A49_C41416467.html?s_z=n_C41416467|
| 6    | —            | 0603 Resistors (47kΩ + 3Ω total)  | —        | $0.25       | LCSC     | Passive Components  |https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FOJAN-FRC0603F3R00TS_C2930150.html  https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_YAGEO-RC0603FR-0747KL_C105579.html|
|||Shipping||3.75|LCSC|||
|      |              | **Total**                         |          |14.52|        |                     |
|||Raspberry Pi zero 2 W+ adapters                        |          |20            |Silverline||https://www.silverlineelectronics.in/products/raspberry-pi-zero-2-silverline-india-authorised-distributor?variant=41596564144297   https://www.silverlineelectronics.in/products/usb-b-male-to-usb-a-female-otg-adaptor-official?variant=41014335176873  https://www.silverlineelectronics.in/products/official-raspberry-pi-micro-sd-card-adapter?variant=41020736995497|
|||PCB+ Shipping||12|JLCPCB|||
|||**TOTAL**||42|||
