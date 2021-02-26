# Commodore CP/M Cartridge for Commodore C64



![](https://github.com/DL2DW/Commodore_CPM_Cartridge/blob/main/Images/Commodore_CPM_Cartridge.jpg)



This is a replica of the Commodore CP/M cartridge, with which it was possible to use CP/M in version 2.2.



## Introduction

In the course of my other Z80 cartridge project here on GitHub, I had first rebuilt the original Commodore CP/M cartridge for analysis purposes.

I kept as much as possible to the original board and only adapted a few footprints to the current parts supply. The board is identical to the original board in dimensions and drillings, so that it also fits into the case of the Commodore version.

Due to the 1:1 reproduction, this cartridge has of course all the corresponding "problems" in terms of compatibility.

I have the card in both 407er, as well as 469 board to run without problems. The installed VIC apparently played no role.

But the used components on the CP/M board do play a role.

Normally "LS" types should be used, thus 74LS00, 75LS04, etc..

But it also helps to try "ALS" and "HCT" types here and there. Unfortunately, I cannot give an ideal recipe here. Only the hint that in the 407 board everything in "LS" is without problems.



## BOM

As mentioned earlier, this parts list should work exactly the same on the older boards. If there are problems, you can try to exchange single parts against "ALS" or "HCT" types. A version with 4MHZ is also sufficient for the CPU.

Please then not all at once, but always first only individually.



| #    | Manufacturer          | Part Number      | Case   | Description                                                  | Quantity |
| ---- | --------------------- | ---------------- | ------ | ------------------------------------------------------------ | -------- |
| 1    | Central Semiconductor | 2N3906           | TO-92  | Bipolar  Transistor PNP Amplifier/Switch 40V 200mA 3-Pin TO-92 Through Hole Box | 1        |
| 2    | Fair-Rite             | 2743005112       | Axial  | Ferrite  Beads Axial 91Ohm 100MHz T/R                        | 6        |
| 3    | Vishay BCcomponents   | A100J15C0GF5TAA  | Axial  | Cap Ceramic  10pF 50V C0G 5% Axial 125C T/R                  | 6        |
| 4    | Vishay  BCcomponents  | A470J15C0GF5TAA  | Axial  | Cap  Ceramic 47pF 50V C0G 5% Axial 125C T/R                  | 1        |
| 5    | KEMET                 | C330C104J5R5TA   | Dipped | Cap Ceramic  0.1uF 50V X7R 5% Radial 5.08mm 125C Bulk        | 12       |
| 6    | Yageo                 | CFR-25JB-52-1K2  | Axial  | RES  1.2K OHM 1/4W 5% AXIAL                                  | 1        |
| 7    | Yageo                 | CFR-25JB-52-2K2  | Axial  | RES 2.2K OHM  1/4W 5% AXIAL                                  | 5        |
| 8    | Yageo                 | CFR-25JB-52-22R  | Axial  | RES  22 OHM 1/4W 5% AXIAL                                    | 1        |
| 9    | Yageo                 | CFR-25JB-52-220R | Axial  | RES 220 OHM  1/4W 5% AXIAL                                   | 1        |
| 10   | Vishay  Dale          | CSC09A014K70GPA  | SIP    | Resistor  Networks & Arrays 9pin 4.7Kohms 2% Bussed          | 3        |
| 11   | Vishay                | MAL203036479E3   | Axial  | Cap Aluminum  47uF 25V -10% to 50% (6 X 10mm) Axial 4.8 Ohm 100mA 3000 hr 85C Taped in Box | 1        |
| 12   | Texas  Instruments    | SN74LS00N        | PDIP   | IC,  74LS, 74LS00, DIP14, 5.25V                              | 1        |
| 13   | Texas Instruments     | SN74LS04N        | PDIP   | IC HEX INVERTER  14-DIP                                      | 1        |
| 14   | Texas  Instruments    | SN74LS12N        | PDIP   | Logic  Gates Triple 3-input Positive-NAND gates with open collector outputs 14-PDIP  0 to 70 | 1        |
| 15   | Texas Instruments     | SN74LS74AN       | PDIP   | TEXAS  INSTRUMENTS  SN74LS74AN  Flip-Flop, with Set and Reset,  Complementary Output, Differential, Positive Edge, D, 13 ns, 33 MHz | 2        |
| 16   | Texas  Instruments    | SN74LS245N       | PDIP   | IC  TXRX NON-INVERT 5.25V 20DIP                              | 3        |
| 17   | ON Semiconductor      | SN74LS283N       | PDIP   | Binary Full  Adder Single 4-Bit 16-Pin PDIP Box              | 1        |
| 18   | ON  Semiconductor     | SN74LS367AN      | PDIP   | I.C.  SN74LS 367 AN                                          | 1        |
| 19   | Texas Instruments     | SN74LS373N       | PDIP   | Latch  Transparent 3-ST 8-CH D-Type 20-Pin PDIP Tube         | 1        |
| 20   | Ixys  Zilog           | Z84C0008PEG      | DIP    | IC  MPU Z80 8MHZ 40DIP                                       | 1        |

------



If you liked my project, I would be very happy about a small coffee donation.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R62T6RN)





# License

The contents of this repository, with the exception of the Docs and Software directories, are released under the following license:

- the "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License" (CC BY-NC-SA 4.0) full text of this license is included in the [LICENSE.CC-NC-BY-SA-4.0](https://github.com/DL2DW/Z80-Card_for_Commodore_C64/blob/main/LICENSE.CC-NC-BY-SA) file and a copy can also be found at https://creativecommons.org/licenses/by-nc-sa/4.0/
