This is a FW for Creality Mainboard 4.2.2
____
STM32F103RET6_creality was renamed STM32F103RE_creality
This error is there specifically to tell you STM32F103RET6_creality is no longer a valid option
____

Drivers A4988
Chip STM32F103RET6
No BLTouch
HEATER_0_MAXTEMP 275
BED_MAXTEMP      120
DEFAULT_AXIS_STEPS_PER_UNIT   { 80, 80, 400, 93 }
DEFAULT_MAX_FEEDRATE          { 500, 500, 10, 50 }
DEFAULT_MAX_ACCELERATION      { 900, 900, 100, 10000 }
DEFAULT_XJERK 10.0
DEFAULT_YJERK 10.0
DEFAULT_ZJERK  0.3
DEFAULT_EJERK  5.0
Z_HOMING_HEIGHT 2
Z_AFTER_HOMING  5
X_BED_SIZE 235
Y_BED_SIZE 235
Z_MAX_POS 250
LCD_BED_TRAMMING
BED_TRAMMING_INSET_LFRB { 30, 30, 30, 30 }
BED_TRAMMING_LEVELING_ORDER { LF, RF, RB, LB }
   *  LB --------- RB 
   *  |  4       3  | 
   *  |             | 
   *  |  1       2  | 
   *  LF --------- RF
#define EEPROM_SETTINGS
