**Omniframe Hardware**

Omniframe is an open source e-paper digital frame. This repository includes the source and fabrication files for the main and secondary boards for driving the [13.3" Monochrome e-ink display](https://www.eink.com/product/detail/VB3300-NCB).

<img width="633" alt="Screenshot 2025-06-12 at 5 02 29 PM" src="https://github.com/user-attachments/assets/05c5da04-90d1-4a51-9e70-42e49fc38262" />

Main Board includes:
* ESP32-S3 N8R2
* TPS65185
* AP61100
* BQ25505
* BQ24040
* MicroSD card slot
  
<img width="480" alt="Screenshot 2025-06-10 at 2 24 29 PM" src="https://github.com/user-attachments/assets/63530276-a8fb-4d9c-a581-4a08e09561d7" />


Secondary Board includes:
* USB Type-C Port
* Pushbutton connected to ESP GPIO

Exports include:
* Gerber files
* Assembly files
* BOM
* STEP files

The main board includes Molex 5023520-series connectors for Solar Array, Battery, and and Secondary Board. By default, connecting the main and secondary boards is done with a ribbon cable with [Molex 5023510500](https://www.digikey.com/en/products/detail/molex/5023510500/4555379) housings. Alternatively, the source files can be modified to accomodate for other connectors. 

To operate the e-paper display using this hardware, flash the [Omniframe Firmware](https://github.com/omniframe-art/Omniframe-Firmware) to the ESP. For converting and transferring images set up the [Private Image Server](https://github.com/omniframe-art/Private-Image-Server).

**Licensing**

The Omniframe framework is licensed under the terms of the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
