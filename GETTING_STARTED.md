# Getting started

These are legacy KiCad breakout-board designs. Start with the source project for the board you want to inspect:

| Board | KiCad project | Schematic | PCB |
| --- | --- | --- | --- |
| LTC3110 supercapacitor backup | [Project](LTC3110_supercap_backup/LTC3110_supercap_backup.pro) | [Schematic](LTC3110_supercap_backup/LTC3110_supercap_backup.sch) | [PCB](LTC3110_supercap_backup/LTC3110_supercap_backup.kicad_pcb) |
| S6AE101A solar harvester | [Project](S6AE101A_solar_harvester/Breakout_S6AE101A.pro) | [Schematic](S6AE101A_solar_harvester/Breakout_S6AE101A.sch) | [PCB](S6AE101A_solar_harvester/Breakout_S6AE101A.kicad_pcb) |
| AS7265x color sensors | [Project](as7265x_color_sensors/as7265x_color_sensors.pro) | [Schematic](as7265x_color_sensors/as7265x_color_sensors.sch) | [PCB](as7265x_color_sensors/as7265x_color_sensors.kicad_pcb) |

Clone the whole repository so local libraries, caches, and supporting files remain alongside the designs:

```sh
git clone https://github.com/mvalancy/IC_Breakouts.git
cd IC_Breakouts
```

The `.pro` and `.sch` files use legacy KiCad formats. Work in a separate branch or copy before allowing a newer KiCad release to migrate them. Keep the accompanying cache libraries when resolving old symbol references. See KiCad's [legacy schematic documentation](https://docs.kicad.org/9.0/en/eeschema/eeschema.html#opening-legacy-schematics).

The solar harvester folder also contains [board previews](S6AE101A_solar_harvester/Readme.md) and [Gerber outputs](S6AE101A_solar_harvester/Gerbers). Treat committed fabrication outputs as historical artifacts: verify them against the source revision before ordering boards. This documentation refresh does not validate electrical behavior or manufacturing readiness.

## License

See [LICENSE.md](LICENSE.md) for the Creative Commons Attribution-ShareAlike 4.0 license.
