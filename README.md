# IntelliHub-Mk.1

The IntelliHub-Mk.1 is a USB Hub designed for people who need more than just that one old USB C slot on your laptop/board. It offers increased functionality in a travel-friendly form factor. I made this project specifically because I am one of the people such a product would appeal to (I have a Macbook Air with not one, but two! whole USB C slots). Recently, while at Undercity (the hackathon), I realized a lot of hardware components still utilize USB A cables and that the lack of a hub was limiting me. This project is my attempt to solve that issue.

![Full Product Render with PCB](https://github.com/pdumpa08/IntelliHub-Mk.1/blob/main/assets/Full_PCB.png?raw=true)

## PCB Design

![PCB](https://github.com/pdumpa08/IntelliHub-Mk.1/blob/main/assets/PCB.png?raw=true)

## Schematic

![Schematic](https://github.com/pdumpa08/IntelliHub-Mk.1/blob/main/assets/Schematic.png?raw=true)

## CAD

![CAD](https://github.com/pdumpa08/IntelliHub-Mk.1/blob/main/assets/Full.png?raw=true)

## Bill of Materials (BOM)

|ID |Name                        |Designator       |Footprint                       |Quantity|Manufacturer Part |Manufacturer   |Supplier|Supplier Part|Price |
|---|----------------------------|-----------------|--------------------------------|--------|------------------|---------------|--------|-------------|------|
|1  |5.1kΩ                       |R1,R2,R3,R4,R5,R6|R0603                           |6       |RMC06035.1K1%N    |Tyohm(幸亚电阻)    |LCSC    |C269716      |0.003 |
|2  |SL2.1A                      |U1               |SOP-16_L10.0-W3.9-P1.27-LS6.0-BL|1       |SL2.1A            |CoreChips(和芯润德)|LCSC    |C192893      |0.261 |
|3  |10UF-C0402                  |U2,U3            |C0402                           |2       |10uF-c0402        |null           |LCSC    |C9900008999  |0.0006|
|4  |USB-AF-90-14.4X13.6-H7.0-DIP|USB1,USB2        |USB-A-TH_C46407                 |2       |903-131A1011D10100|精拓金            |LCSC    |C46407       |0.043 |
|5  |TYPE-C-31-M-12              |USBC1,USBC2,USBC4|USB-C_SMD-TYPE-C-31-M-12        |3       |TYPE-C-31-M-12    |韩国韩荣           |LCSC    |C165948      |0.174 |
|6  |Case                        |-                |-                               |1       |-                 |Printing Legion|Printing Legion|-            |~$6   |

Estimated Subtotal for PCB w/ Economic Assembly and Case (w/ shipping and taxes): $64
Actual Subtotal (after coupon): $44
