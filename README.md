# Yamaha V99x8 Tester for MSX
Simple Arduino sketch & PCB to test if a V9958 is real.<br>

PCB is designed & Arduino sketch generated (by Claude) but nothing is tested or sanity checked yet (3/Jul/2026).<br>

Idea is to query the "identification number" of the chip from bits 1-5 of status register S#1:
- 0 = V9938
- 1 = V9948
- 2 = V9958
- 3 = V9968
- 4 = V9978


![3D of PCB](/Images/Yamaha_VDP_Tester_3D.png)

