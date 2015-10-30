This repo houses my current cleanflight settings, copies of good settings I've found along the way, Blackbox flight logs of all my flights, links of interest, etc. It's unorganized, and probably only of interest to me.

# Quadcopter
Currently flying:
- QAV250
- 5" Bullnose props
- Cobra 2204 2300kv motors
- Luminier 20A ESC
- Naze32 acro with BorisB Betaflight firmware.

# Blackbox Logs
Folder labels: `MM.DD.YY`

## Common commands
Flashing the Motolabs Tornado with a .bin file:
`/opt/local/bin/dfu-util -s 0x08000000 -a 0 -d 0483:df11 -D ~/Github/public-projects/quadcopter-data/betaflight/betaflight_MOTOLAB.bin`