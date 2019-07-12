# NanoPi GPS/RTC HAT

GPS Tested, RTC NOT Tested!

Note that you need to compile `GPSD` and `Chrony` yourself as the version supplied with Armbian DOES NOT WORK!

# BOM

| Id | Designator | Package                                         | Quantity | Designation       |
|----|------------|-------------------------------------------------|----------|-------------------|
| 1  | U2         | SOIC-16W_7.5x10.3mm_P1.27mm                     | 1        | DS3231M           |
| 2  | SW1        | SW_SPST_EVQPE1 淘宝贴片轻触开关，长方形的6mm长  | 1        | SW_Push           |
| 3  | R4,R3,R2   | R_0805_2012Metric                               | 3        | NP                |
| 4  | C2         | C_0805_2012Metric                               | 1        | 1u                |
| 5  | J4         | PinSocket_1x08_P2.54mm_Vertical 1P8 母头        | 1        | Conn_01x08_Female |
| 6  | J3         | PinSocket_1x12_P2.54mm_Vertical 1P12 母头       | 1        | Conn_01x12_Female |
| 7  | R1         | R_0805_2012Metric                               | 1        | 10                |
| 8  | L1         | L_0805_2012Metric                               | 1        | 27n               |
| 9  | J2         | PinHeader_2x12_P2.54mm_Vertical 2P12 母头       | 1        | NanoPi_GPIO       |
| 10 | C1         | C_0805_2012Metric                               | 1        | 47p               |
| 11 | BT1        | BatteryHolder_Seiko_MS621F 贴片纽扣电池 3V      | 1        | Battery_Cell      |
| 12 | J1         | U.FL_Molex_MCRF_73412-0110_Vertical 淘宝 uFL 座 | 1        | Conn_Coaxial      |
| 13 | U1         | KH-1110 立创，可买 JS-U810 （兼容）             | 1        | KH-1110-UB8X      |

# LICENSE

CERN OHL version 1.2
