## Startup code
```
G21               ;metric values
G90               ;absolute positioning
M107              ;start with the fan off
G28 X0 Y0         ;move X/Y to min endstops
G28 Z0            ;move Z to min endstops
G1 Z15.0 F3000    ;move the platform down 15mm
G92 E0            ;zero the extruded length
G1 F200 E3        ;extrude 3mm of feed stock
G92 E0            ;zero the extruded length again
G1 F3000
M117 Printing...
```

## End Code
```
M104 S0                      ;extruder heater off
M140 S0                      ;heated bed heater off (if you have it)
G91                          ;relative positioning
G1 E-1 F300                  ;retract the filament a bit before lifting the nozzle, to release some of the pressure
G1 Z+0.5 E-5 X-20 Y-20 F3000 ;move Z up a bit and retract filament even more
G28 X0 Y0                    ;move X/Y to min endstops, so the head is out of the way
M84                          ;steppers off
G90                          ;absolute positioning
```
