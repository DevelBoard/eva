# Develer EVA01 Project
Schematics and Gerber for DevelBoard Evaluation, and shield boards.

## EVA01 Releases

### EVA01 Rev.3 (eva01-R3)
 * PCB release Rev.C (pcb-eva01-Rev-C)
 * Move WLAN_PWR singal form PB29 to PE5 pin.
 * Silk screen cosmetic fixes
 
### EVA01 Rev.2 (eva01-R2)
 * PCB release Rev.B (pcb-eva01-Rev-B)
 * Minor fixes
 * Change USB Host connector position
 * Reduce backup battery size
 * Add Bridge diode on Power supply connector
 * Cosmetic fixes
 * Issues:
   * WiFi/BlueTooth enable: Put R10 to NP and R11 to 22R.

### EVA01 Rev.1 (eva01-R1)
 * First Release
 * PCB release Rev.A (pcb-eva01-Rev-A)
 * Issues:
   * J3 Connector Wrong Power Jack polarity -> Inside pin is GND, and output is +24V
 
## Shield Board Releases

### SHIELD Display 7'', CAN, RS232, RS485 Rev.0 (shield_can-display-R0)
* First Release: Automotive shield version. This shield provvide CAN, RS485 and RS232 peripherals, and LCD Display 7'' 800x480 with integrated resisteve touch. The board support the external capacitive touch frame.
 * PCB release Rev.A (pcb-shield_can-display-Rev-A)
 * Issues:
   * J9 Connector mirrored -> the capacitive touch frame not work.
   * Missing pull down on lcd backlight enable

### SHIELD Display 4.3'' Rev.1 (shield_display_4.3-R1)
* First Release: Display shield version. The shield support LCD Display 4.3'' 480x272  with integrated resisteve touch.
 * PCB release Rev.A (pcb-shield_display_4.3-Rev-A)
 * Issues:
   * Missing pull down on lcd backlight enable

### SHIELD IO Rev.0 (shield_io-R0)
 * First release: Generic IO shield this shield provvide 4 Relay SPDT, 2 Digital input Optocoupled, 2 Digital Input, 4 ADC input, 2 ADC Current shunt, 2 Voltage DAC and 2 Current DAC.


