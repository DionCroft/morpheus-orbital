# Morpheus ORBITAL

A KiCad hardware prototype for a portable 7.3-inch colour e-paper device. The board combines an ESP32-S3, USB-C, microSD, environmental sensing, and a single-cell battery power path. The six-layer ORBITAL layout keeps user connectors accessible and reserves space for the display flex and antenna.

## Open the design

Open [Morpheus.kicad_pro](circuit_design/Morpheus/Morpheus.kicad_pro) in KiCad 10.0.4 or a compatible KiCad 10 installation. Install KiCad's standard libraries and optional 3D model library, and keep the project directory structure intact. The [reference BOM](Morpheus-BOM.csv) identifies fitted and optional parts. The repository contains the editable schematic, routed PCB, project libraries, and local 3D models.

## Prototype status

This snapshot matches the reviewed CAD revision. Its full PCB DRC reported zero unconnected items, three warnings, and 50 reviewed footprint-parity records. Electrical and mechanical hardware qualification remains open. In particular, verify USB impedance against the fabricator's finished stackup, selective filled/capped vias, display bias and startup behaviour, battery/temperature sensing, display connector fit, RF performance, and assembly clearances. Use those checks and the exact supplied parts before committing to fabrication.

## License and attribution

Original Morpheus hardware design material is licensed under [CERN-OHL-S-2.0](LICENSES/CERN-OHL-S-2.0.txt). The source location is https://github.com/DionCroft/morpheus-orbital. The crest artwork and personal signature are retained on the board and are outside the hardware license. KiCad library material retains its upstream terms. See [third-party and artwork notices](THIRD_PARTY_NOTICES.md).
