# AnetA8 Custom change

Change made to the Marlin configuration for AnetA8 

change: 

```
#define STRING_CONFIG_H_AUTHOR "(Arnaud, Anet config)" // Who made the changes.
#define CUSTOM_MACHINE_NAME "3D Maker"
```

uncomment : 
```
#define AUTO_BED_LEVELING_BILINEAR
Activate auto bed leveling
#define LCD_BED_LEVELING
use LCD controler for bed leveling
#define PROBE_MANUALLY
no sensor, but bed leveling done manually with the menu
```
