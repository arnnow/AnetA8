# AnetA8 Custom change

Change made to the Marlin configuration for AnetA8 

## Printer Name and info
change: 

```
#define STRING_CONFIG_H_AUTHOR "(Arnaud, Anet config)" // Who made the changes.
#define CUSTOM_MACHINE_NAME "3D Maker"
```


## Auto (Manual with LCP input) - Bed leveling
uncomment : 
```
#define AUTO_BED_LEVELING_BILINEAR
Activate auto bed leveling
#define LCD_BED_LEVELING
use LCD controler for bed leveling
#define PROBE_MANUALLY
no sensor, but bed leveling done manually with the menu
```

# Firmware link

* https://www.youtube.com/watch?v=5xeo9G3kXEQ
* https://www.youtube.com/watch?v=2uX5_rI1QM8
* http://honzakasik.cz/2017/12/17/marlin-firmware-anet-a8.html
* https://www.youtube.com/watch?v=WWDkZtWwd6I&index=1&list=PLlcMt_sdtxsCmJl5oZLiO3Ub6LN2GBwIe

### Firware configuration
* Anet Firmware : https://www.3dprintersbay.com/anet-a8-a6-firmwares-latest
* http://marlinfw.org/docs/configuration/configuration.html#configuration.h
* https://www.youtube.com/watch?v=0pt_b2ZizQM

