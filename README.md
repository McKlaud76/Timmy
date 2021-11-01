# Timmy

![Timmy](/Docs/TC2048_PCB_03.png)

### Timex Computer 2048 clone with 80KB RAM on board.

The clone (v.0.3) includes:

* Z80A (3.5MHz) CPU,
* Timex SCLD or its replacement called SCLD Q,
* 16KB lower RAM,
* 2 x 32KB upper RAM (bank switching controlled by #FF port),
* 2 x 16KB ROM (selectable),
* AY-3-8910 sound chip controlled via SCLD ports (Timex or ZX128K),
* improved Kempston joystick interface,
* RGB and composite video outputs,
* compatible with TC2048 keyboard,
* RESET button,
* PCB in dimensions and size of the Timex Computer 2048 board,
* MH-M18 Bluetooth (BT) audio module for wireless tape loadig.

Changes to previous revision:
* SCLD footprint corrections,
* corrected edge connector layout,
* added BT audio module,
* added PSG I/O port A connector.

For detailed information please visit: (https://www.speccy.pl/forum/index.php?topic=6033.0 "Timmy")

Some of tests to watch: (https://www.youtube.com/watch?v=dC0ZgcBu8rQ&list=PLeEjSz45t7SoUN8s2FDAEhrHg98INT9Z2 "YouTube")

Comparision Timmy v0.2 with TC2048 Board:
![TC2048vsTimmy](/Docs/Timmyv0.2.jpg)

Testing setup (v1.1):
![Testbench](/Docs/SCLDv3_02.jpeg)

Colour test output (v1.1):
[![Testing Timmy](/Docs/Timmy_RGB_01.jpg)](https://youtu.be/dC0ZgcBu8rQ "Testing Timmy")

--------------------------------------------------------------------------------

*This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0).*

*No Warranty of the Project. The Issuer makes no express or implied warranty of any kind whatsoever with respect to the Project.*
