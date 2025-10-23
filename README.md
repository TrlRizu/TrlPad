# TrlPad

TrlPad is a 4-key macropad with a rotary encoder, an OLED display.

## Features

- 4 programmable mechanical keys (MX-style switches)
- Rotary encoder with push-button for multi-function input
- 0.91" 128x32 OLED dispvlay (SSD1306)
- Powered by Seeed Studio XIAO nRF52840 (Bluetooth + USB)
- Custom PCB

## How it evolved

### The initial concept
The design concept was to be something akin to a pedal effect. A sketch of what I thought it'd be:

![concept-1.jpg](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTU4OSwicHVyIjoiYmxvYl9pZCJ9fQ==--99acb60c861b588bb9ba950350989237539b35af/concept-1.jpg)

### Final
Yeah, it's rather different but this is more feasible and it's simple yet punk-y.

![image.png](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NDA1NSwicHVyIjoiYmxvYl9pZCJ9fQ==--13515724b4d5ed1d60a12a15c5ef635fe72e6fe0/image.png)

### PCB
Below is the schematic:

![Schematic](screenshots/schematic.png)


Below is the PCB routing:

![routing](screenshots/PCB.png)
---

## Bill of Materials (BOM)
| # | Reference | Value | Footprint | Qty | Link | Price (USD) | Running Price (USD) |
|---|------------|--------|------------|-----|-------|----------------|----------------------|
| 1 | C1, C2 | 10nF | Capacitor_SMD:C_0603_1608Metric_Pad1.08x0.95mm_HandSolder | 2 | [AliExpress](https://www.aliexpress.com/item/1005002769470761.html) | 0.60 | 0.49 |
| 2 | D1, D2, D3, D4 | D | Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal | 4 | [AliExpress](https://www.aliexpress.com/item/1005007625866819.html) | 1.41 | 2.01 |
| 3 | D5 | 1N4148W | Diode_SMD:D_SOD-123 | 1 | [AliExpress](https://www.aliexpress.com/item/1005007160279747.html) | 1.95 | 3.96 |
| 4 | R1 | 806k | Resistor_SMD:R_0805_2012Metric | 1 | [AliExpress](https://www.aliexpress.com/item/1005008964311488.html) | 0.66 | 5.10 |
| 5 | R2 | 2M | Resistor_SMD:R_0805_2012Metric | 1 | [AliExpress](https://www.aliexpress.com/item/1005008964311488.html) | 0.48 | 5.10 |
| 6 | R3, R4, R5, R8 | 10K | Resistor_SMD:R_0603_1608Metric_Pad0.98x0.95mm_HandSolder | 4 | [AliExpress](https://www.aliexpress.com/item/1005009805187579.html) | 1.00 | 6.10 |
| 7 | SW1, SW2, SW3, SW4 | SW_Push | Button_Switch_Keyboard:SW_Cherry_MX_1.00u_PCB | 4 | [AliExpress](https://www.aliexpress.com/item/1005006255961111.html) | 1.01 | 7.11 |
| 8 | SW5 | RotaryEncoder_Switch | Rotary_Encoder:RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm | 1 | [AliExpress](https://www.aliexpress.com/item/1005006693443387.html) | 0.63 | 7.74 |
| 9 | TP1, TP2 | TestPoint | TestPoint:TestPoint_Pad_D2.0mm | 2 | — | — | — |
| 10 | U1 | XIAO-nRF52840-SMD | Modified:modified-XIAO-nRF52840-SMD | 1 | [AliExpress](https://www.aliexpress.com/item/1005006988954136.html) | 10.11 | 17.85 |
| 11 | U2 | 128x32_OLED_S | zzz_Project:SSD1306-0.91-OLED-4pin-128x32 | 1 | [AliExpress](https://www.aliexpress.com/item/1005008640132638.html) | 2.24 | 20.09 |
| 12 | Shipping costs | — | for AliExpress check cart.png | — | — | 5.24 | 25.33 |
| 13 | 3D Printed case | — | check screenshot 3dCase_bill.png | — | [Upload to 3Ding](https://print.3ding.in/upload) | 16.29 | 41.62 |
| 14 | PCB | — | from JLPCB, check screenshot jlcpcb.png | — | — | 7.56 | 49.18 |
|   | **Total** |  |  |  |  |  | **49.18** |


####  Note: I am trying to get the case 3D printed using #printing-legion, or if that doesn't work out, I'll cover the cost on my own!
---
