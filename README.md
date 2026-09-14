# USB HUB
- The Files uploaded are for my custom USB HUB which can be reviewed on any EDA platform. It has an Upstream port of C-Type and 4 downstream ports, 2 are A-type and 2 are C-type. It can be used for a laptop to connect more USB devices allowing u to connect upto 4 more devices !!
# PCB Schematic
<img width="931" height="654" alt="Screenshot 2026-06-12 215259" src="https://github.com/user-attachments/assets/d2a08c0f-9a00-4d4f-8c3c-988390521ae6" />

# PCB render
<img width="1038" height="878" alt="Screenshot 2026-06-13 161200" src="https://github.com/user-attachments/assets/4ea97ed1-4590-4740-b4e8-a8149ed60917" />

# PCB Design
<img width="1113" height="753" alt="Screenshot 2026-06-13 161341" src="https://github.com/user-attachments/assets/e007a310-9097-4d1d-8233-b1eb1c09530a" />

# BOM
|Name                 |Description                                                                                 |Quantity|Total Cost|Link                                                                                                                               |Distributor|
|---------------------|--------------------------------------------------------------------------------------------|--------|----------|-----------------------------------------------------------------------------------------------------------------------------------|-----------|
|PCB                  |Main PCB+Assembly                                                                           |1       |$27.59    |https://jlcpcb.com/                                                                                                                |JLCPCB     |

# BOM of All Components in the PCB
|No.                                         |Quantity                        |Comment|Designator             |Footprint                       |Value|Manufacturer Part    |Manufacturer   |Supplier Part|Supplier|
|--------------------------------------------|--------------------------------|-------|-----------------------|--------------------------------|-----|---------------------|---------------|-------------|--------|
|1                                           |8                               |1uF    |C1,C2,C3,C4,C5,C6,C7,C8|C0603                           |1uF  |C0603X105K025T       |IHHEC(禾伸堂)     |C559292      |LCSC    |
|2                                           |3                               |100nF  |C9,C10,C11             |C0603                           |100nF|CC0603KRX7R9BB104    |YAGEO(国巨)      |C14663       |LCSC    |
|3                                           |1                               |10kΩ   |R1                     |R0603                           |10kΩ |0603WAF1002T5E       |UNI-ROYAL(厚声)  |C25804       |LCSC    |
|4                                           |5                               |5.1kΩ  |R2,R3,R4,R5,R6         |R0603                           |5.1kΩ|0603WAF5101T5E       |UNI-ROYAL(厚声)  |C23186       |LCSC    |
|5                                           |1                               |SL2.1s |U1                     |SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL|     |SL2.1s               |CoreChips(和芯润德)|C2684433     |LCSC    |
|6                                           |3                               |TYPE-C 16PIN 2MD(073)|USB1,USB2,USB5         |USB-C-SMD_TYPE-C-16PIN-2MD-073  |     |TYPE-C 16PIN 2MD(073)|SHOU HAN(首韩)   |C2765186     |LCSC    |
|7                                           |2                               |10.0 QHHTZB6.3|USB3,USB4              |USB-A-TH_10.0QHHTZB6.3          |     |10.0 QHHTZB6.3       |SHOU HAN(首韩)   |C668591      |LCSC    |
