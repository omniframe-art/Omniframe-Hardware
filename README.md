**Omniframe Hardware**

Omniframe is an open source e-paper digital frame. This repository includes the source and fabrication files for the main and secondary boards for driving the [13.3" Monochrome e-ink display](https://www.eink.com/product/detail/VB3300-NCB).

Exports include:
* Gerber files
* Assembly files
* BOM
* STEP files

The main board includes Molex 5023520-series connectors for Solar Array, Battery, and and Secondary Board. By default, connecting the main and secondary boards is done with a ribbon cable with [Molex 5023510500](https://www.digikey.com/en/products/detail/molex/5023510500/4555379) housings. Alternatively, the source files can be modified to accomodate for other connectors. 

To operate the e-paper display using this hardware, flash the [Omniframe Firmware](https://github.com/omniframe-art/Omniframe-Firmware) to the ESP. For converting and transferring images set up the [Private Image Server](https://github.com/omniframe-art/Private-Image-Server).

**Licensing**

The Omniframe framework is licensed under the terms of the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
