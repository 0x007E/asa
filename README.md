[![Version: 1.0 Release](https://img.shields.io/badge/Version-1.0%20Release-green.svg)](https://github.com/0x007e/asa) ![Build](https://github.com/0x007e/asa/actions/workflows/release.yml/badge.svg) [![License CC By-NC-SA](https://img.shields.io/badge/Hardware-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

# `ASA` - Audio Signal Amplifier

The `ASA` is a board with an [LM386](#additional-information) or any other audio signal amplifier. The board itself can be driven with a voltage between `5-12V`. It adds and amplifies the given  input signal(s) with a gain between `~50-200` to a connected speaker. If the supply of the board is available the `green` led is `on`. The board itself provides a reverse polarity protection.

| Experience | Level |
|:------------|:-----:|
| Soldering   | ![?%](https://progress-bar.xyz/40?progress_color=00ff00&suffix=%20Medium&width=120) |

# Downloads

| Type      | File               | Description              |
|:---------:|:------------------:|:-------------------------|
| Schematic | [pdf](https://github.com/0x007E/asa/releases/latest/download/schematic.pdf) / [cadlab](https://cadlab.io/project/30571/main/files) | Schematic files |
| Board | [pdf](https://github.com/0x007E/asa/releases/latest/download/pcb.pdf) / [cadlab](https://cadlab.io/project/30571/main/files) | Board file |
| Drill | [pdf](https://github.com/0x007E/asa/releases/latest/download/drill.pdf) | Drill file |
| BoM | [xlsx](https://github.com/0x007E/asa/releases/latest/download/bom.xlsx) / [html](https://github.com/0x007E/asa/releases/latest/download/ibom.html)          | Bill of Material as Excel/interactive HTML |
| PCB    | [zip](https://github.com/0x007E/asa/releases/latest/download/kicad.zip) / [tar](https://github.com/0x007E/asa/releases/latest/download/kicad.tar.gz)    | KiCAD/Gerber/BoM/Drill files       |

# Hardware

The pcb is created with `KiCAD`. All files are built with `github actions` so that they are ready for a production environment.

## PCB

The circuit board is populated on one side. The best way for soldering the `SMD` components is within a vapor phase soldering system and for the `THT` components with a standard system.

### Top Layer

![Top Layer](https://github.com/0x007E/asa/releases/latest/download/top.kicad.png)

### Bottom Layer

![Bottom Layer](https://github.com/0x007E/asa/releases/latest/download/bottom.kicad.png)

# Configuration

To gain configure of the `ASA` can be set with the `RV2` trimmer. If the trimmer is not solderd the standard gain is around `~20`.

# Additional Information

| Type  | Link                                               | Description                                 |
|:------|:--------------------------------------------------:|:--------------------------------------------|
| LM386 | [pdf](https://www.ti.com/lit/ds/symlink/lm386.pdf) | Low Voltage Audio Power Amplifier Datasheet |

---

R. GAECHTER
