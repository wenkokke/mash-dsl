# Mash DSL
A low-level DSL for describing mashing and brewing recipes 🍺

```
Pump to_grain on
Pump from_grain on
Heat to 45C
Echo "Mash starting"
Mash at 45C for 15m
Mash at 60C for 15m
Mash at 65C for 30m
Mash at 75C for 10m
Echo "Mash finished"
Pump to_grain off
Wait for 5m
Pump from_grain off
Echo "Please reconfigure pumps"
Wait for user
Echo "Sterilisation starting"
Boil for 5m
Echo "Sterilisation finished"
```
