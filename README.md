# Ender-3 V3 SE (Klipper Config and Macros)

This repository contains the Klipper configuration and macros for the Ender 3 V3 SE.

## Klipper Installation Guide

Follow this guide to install Klipper on your Ender 3 V3 SE: [Klipper Installation Guide](https://artamis.me/projects/klipper_guide/)

>[!Note]
> The guide uses a different configuration file available here: [Bootuz-Dinamon Ender 3 V3 SE Klipper Config](https://github.com/bootuz-dinamon/ender3-v3-se-full-klipper)  
> However, my configuration is derived from it, with several issues fixed and improved macros. You are free to use either configuration based on your preference.

## Slicer Setup (OrcaSlicer/Creality Print)

### Start G-Code
```ini
PRINT_START BED=[bed_temperature_initial_layer_single] EXTRUDER=[nozzle_temperature_initial_layer]
```

### End G-Code
```ini
PRINT_END
```
