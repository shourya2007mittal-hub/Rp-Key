# Rp-Key

<img width="1200" height="647" alt="Screenshot 2026-08-20 003324" src="https://github.com/user-attachments/assets/8f012880-c86e-49e1-b08f-6e6b5b8bc2aa" />


SO I wanted to make something like YubiKey but to Enter passwords onto your online accounts or offline password ( like laptop passwords / security passwords) and the most important thing that I focused was that you could enter a password in public without anyone watching it . This add extra privacy to your workflow . So the main focus of my design was to make it small . SO I used RP2350A as micro-controller because it doesn't need an external oscillator hence it saves space on the board . Also there are 4 switches . So you could enter upto 4 different passwords as per your need . There is a boot pin also so that you could update the board as per your need .  The Design is compatible with USB-A and it plugs in perfectly onto it with all the connectors pins aligned . other then that the board has a 3.3V voltage regulator for the MCU and a LED. 


## Why This

It is a simple and is compile too that can be directly plugged on Laptop to enter a password also no one would see you entering the password so it's even better. 

## Features

- Based on RP-2035A Chip
- Has MCP1700x-330xxTT as Voltage Regulator
- has 4 button to enter 4 different password
- had a boot pin as well to update password
- Plugs directly onto type A female


# Project Bill of Materials (BOM) & Cost Summary

## 📦 Components List

| Comment / Part | Quantity | Total Price ($) | Part Link |
| :--- | :---: | :---: | :--- |
| **4.7u** | 6 | $0.1368 | [JLCPCB Link](https://jlcpcb.com/partdetail/24469-CL05A475MP5NRNC/C23733) |
| **100n** | 4 | $0.0216 | [JLCPCB Link](https://jlcpcb.com/partdetail/1877-CL05B104KO5NNNC/C1525) |
| **10uF** | 4 | $0.1548 | [JLCPCB Link](https://jlcpcb.com/partdetail/20411-CL10A106KP8NNNC/C19702) |
| **15p** | 4 | $0.0188 | [JLCPCB Link](https://jlcpcb.com/partdetail/1900-0402CG150J500NT/C1548) |
| **3.3u** | 2 | $1.6456 | [JLCPCB Link](https://jlcpcb.com/partdetail/KOHERelec-MDA40203R3M/C2847470) |
| **1k** | 4 | $0.0320 | [JLCPCB Link](https://jlcpcb.com/partdetail/12256-0402WGF1001TCE/C11702) |
| **10k** | 2 | $0.0132 | [JLCPCB Link](https://jlcpcb.com/partdetail/26274-0402WGJ0103TCE/C25531) |
| **27 ohm** | 4 | $0.0362 | [JLCPCB Link](https://jlcpcb.com/partdetail/25843-0402WGF270JTCE/C25100) |
| **33** | 2 | $0.0068 | [JLCPCB Link](https://jlcpcb.com/partdetail/25848-0402WGF330JTCE/C25105) |
| **1K** | 2 | $0.0120 | [JLCPCB Link](https://jlcpcb.com/partdetail/21904-0603WAF1001T5E/C21190) |
| **SW_Push** | 10 | $3.7180 | [JLCPCB Link](https://jlcpcb.com/partdetail/Korean_HropartsElec-K5_1672SN01/C502360) |
| **RP2350A** | 2 | $3.3980 | [JLCPCB Link](https://jlcpcb.com/partdetail/RaspberryPi-RP2350A/C42411118) |
| **MCP1700x-330xxTT** | 2 | $1.0314 | [JLCPCB Link](https://jlcpcb.com/partdetail/MicrochipTech-MCP1700_3002ETO/C185558) |
| **ABM8-272-T3** | 5 | $1.4705 | [JLCPCB Link](https://jlcpcb.com/partdetail/AbraconLLC-ABM8_272T3/C20625731) |
| **USB_A_PCB_Edge_receptacle** | - | - | - |



---

## 💰 Charge Details & Manufacturing Breakdown

### 🛠️ PCB Fabrication & Assembly Fees
| Item / Description | Price ($) |
| :--- | :---: |
| **PCB Base Price** | $2.00 |
| **Via Covering** | $0.00 |
| **Special Offer** | $2.00 |
| **Setup Fee** | $8.18 |
| **Stencil** | $1.53 |
| **Panel** | $0.00 |
| **Large Size** | $0.00 |
| **Components (12 items)** | $11.65 |
| **Extended components fee** | $12.28 |
| **SMT Assembly** | $0.38 |
| **Hand-soldering labor fee** | $3.58 |
| **Manual Assembly** | $0.10 |
| **Nitrogen reflow soldering** | $0.85 |

### 💵 Cost Totals Summary
| Category | Total Price ($) |
| :--- | :---: |
| **PCB Price Total** | **$2.00** |
| **PCB Shipping** | **$9.68** |
| **Economic PCBA Price Total** | **$48.23** |
| **Grand Total** | **$50.23** |




### Schematic 
<br>
<img width="897" height="547" alt="Screenshot 2026-08-16 184217" src="https://github.com/user-attachments/assets/ef426b57-eb0f-4c22-b0a8-4536981eb2c0" />


<br>

### PCB Design
<img width="1166" height="351" alt="Screenshot 2026-08-16 193003" src="https://github.com/user-attachments/assets/8d395339-1058-4e03-b68e-32c250cd062b" />

### 3D Design

<img width="742" height="507" alt="Screenshot 2026-08-09 154333" src="https://github.com/user-attachments/assets/aeae65be-9acf-4064-8113-64f2a22c1c7e" />


