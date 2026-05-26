# Ender-3 V3 SE (Klipper Config and Macros)

This repository contains the Klipper configuration and macros for the Ender 3 V3 SE.

*Credit: This configuration is derived from the [Bootuz-Dinamon Ender 3 V3 SE Klipper Config](https://github.com/bootuz-dinamon/ender3-v3-se-full-klipper), with several issues fixed and improved macros.*

## Klipper Installation Guide

Follow this guide by [@athem1s](https://github.com/athem1s) to install Klipper on your Ender 3 V3 SE: [Klipper Installation Guide](https://artamis.me/projects/klipper_guide/)

## Slicer Setup

>[!IMPORTANT]
> Enable `Exclude Objects` and `Label Objects` in your slicer settings for adaptive bed mesh and purge to function correctly.

### Start G-Code (OrcaSlicer/Creality Print)
```ini
PRINT_START BED=[bed_temperature_initial_layer_single] EXTRUDER=[nozzle_temperature_initial_layer]
```

### Start G-Code (Cura)
```ini
PRINT_START BED={material_bed_temperature} EXTRUDER={material_print_temperature}
```

### End G-Code
```ini
PRINT_END
```
