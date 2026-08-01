# flinx

<img src="https://static.ayukmr.com/repos/flinx/3.png" height="400">

nRF52833-based low-profile 40% keyboard.

## Schematic

<img src="https://static.ayukmr.com/repos/flinx/1.png" height="400">

## PCB

<img src="https://static.ayukmr.com/repos/flinx/2.png" height="400">

## BOM

| Reference          | Qty | Value                       | DigiKey Part #              | $     |
|:-------------------|:----|:----------------------------|:----------------------------|:------|
| AE1                | 1   | Antenna                     | [712-2450AT18B0100001ECT-ND](https://www.digikey.com/en/products/detail/johanson-technology-inc/2450AT18B0100001E/1560677)  | $0.55 |
| C1,C2              | 2   | 12 pF                       | [311-1059-1-ND](https://www.digikey.com/en/products/detail/yageo/CC0603JRNPO9BN120/302793)               | $0.20 |
| C3,C4,C7,C8,C9,C15 | 6   | 4.7 uF                      | [311-1453-1-ND](https://www.digikey.com/en/products/detail/yageo/CC0603ZRY5V5BB475/2833618)               | $0.98 |
| C5                 | 1   | 1 pF                        | [311-1049-1-ND](https://www.digikey.com/en/products/detail/yageo/CC0603CRNPO9BN1R0/302783)               | $0.10 |
| C6,C14             | 2   | 1.2 pF                      | [311-3825-1-ND](https://www.digikey.com/en/products/detail/yageo/CC0603BRNPO9BN1R2/5883418)               | $0.26 |
| C10                | 1   | 100 pF                      | [311-1069-1-ND](https://www.digikey.com/en/products/detail/yageo/CC0603JRNPO9BN101/302803)               | $0.10 |
| C11,C16,C17,C18    | 4   | 100 nF                      | [311-1343-1-ND](https://www.digikey.com/en/products/detail/yageo/CC0603ZRY5V9BB104/2103081)               | $0.40 |
| C12,C13            | 2   | 10 uF                       | [311-1781-1-ND](https://www.digikey.com/en/products/detail/yageo/CC0603KRX5R5BB106/5195190)               | $0.44 |
| D1,D2,D3,...,D48   | 48  | D                           | [1655-1N4148WCT-ND](https://www.digikey.com/en/products/detail/smc-diode-solutions/1N4148W/6022450)           | $2.96 |
| J1                 | 1   | USB_C_Receptacle_USB2.0_14P | [670-DX07S016JA3R1500CT-ND](https://www.digikey.com/en/products/detail/jae-electronics/DX07S016JA3R1500/12354006)   | $2.02 |
| L1,L3,L4           | 3   | 4.7 nH                      | [712-LRC0603CS4N7GV001TCT-ND](https://www.digikey.com/en/products/detail/johanson-technology-inc/LRC0603CS4N7GV001T/1561296) | $0.30 |
| L2                 | 1   | 2.2 nH                      | [535-11535-1-ND](https://www.digikey.com/en/products/detail/abracon-llc/AIMC-0603-2N2S-T/2662889)              | $0.10 |
| L5                 | 1   | 2.7 nH                      | [712-LRC0603CS2N7GV001TCT-ND](https://www.digikey.com/en/products/detail/johanson-technology-inc/LRC0603CS2N7GV001T/1561291) | $0.10 |
| L6                 | 1   | 3.3 nH                      | [712-LRC0603CS3N3GV001TCT-ND](https://www.digikey.com/en/products/detail/johanson-technology-inc/LRC0603CS3N3GV001T/1561292) | $0.10 |
| R1,R2              | 2   | 22 Ω                        | [311-22.0HRCT-ND](https://www.digikey.com/en/products/detail/yageo/RC0603FR-0722RL/727055)             | $0.20 |
| R3,R4              | 2   | 5.1k Ω                      | [311-5.10KHRCT-ND](https://www.digikey.com/en/products/detail/yageo/RC0603FR-075K1L/727268)            | $0.20 |
| R6                 | 1   | 75k Ω                       | [311-75.0KHRCT-ND](https://www.digikey.com/en/products/detail/yageo/RC0603FR-0775KL/727378)            | $0.10 |
| R7                 | 1   | 10k Ω                       | [311-10.0KHRCT-ND](https://www.digikey.com/en/products/detail/yageo/RC0603FR-0710KL/726880)            | $0.10 |
| SW49               | 1   | SW_SPDT                     | [EG5720CT-ND](https://www.digikey.com/en/products/detail/e-switch/EG1215AA/9559277)                 | $0.99 |
| U1                 | 1   | nRF52833_QDxx               | [4823-NRF52833-QDAA-RCT-ND](https://www.digikey.com/en/products/detail/nordic-semiconductor-asa/NRF52833-QDAA-R/13996159)   | $5.61 |
| U2                 | 1   | TP4057                      | [4518-TP4057CT-ND](https://www.digikey.com/en/products/detail/umw/TP4057/17635237)            | $0.24 |
| Y1                 | 1   | 32MHz                       | [644-CS06654-32MCT-ND](https://www.digikey.com/en/products/detail/ndk-nihon-dempa-kogyo-co-ltd/CS06654-32M/9172029)        | $0.52 |
