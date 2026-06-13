# Li Charger

KiCad PCB design for a single-cell lithium-ion battery charger, with a 5V USB-C input and 10-LED charge level indicator.

## Features

- **BQ24092** linear charger IC (Texas Instruments)
- **LM3914** dot/bar display driver for charge indication
- USB-C power input
- JST battery connector

## Project structure

```
├── hardware/              KiCad schematic, PCB, and custom libraries
│   ├── Li Charger.kicad_pro
│   ├── Li Charger.kicad_sch
│   ├── Li Charger.kicad_pcb
│   └── libs/              Custom symbol and footprint imports
├── manufacturing/
│   └── gerbers/           Fabrication outputs (Gerber + drill files)
├── datasheets/        	   Component reference PDFs
├── 3D models/             Component models not included in standard libs
```
## Manufacturing

Gerber and drill files for PCB fabrication are in `manufacturing/gerbers/`.

## Datasheets

| Part     | Document                                      |
|----------|-----------------------------------------------|
| BQ24092  | [docs/datasheets/bq24092.pdf](docs/datasheets/bq24092.pdf) |
| LM3914   | [docs/datasheets/lm3914.pdf](docs/datasheets/lm3914.pdf)   |
