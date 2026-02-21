
# Gardening Robot Gantry (DTU Skylab)


Modular Cartesian gardening robot inspired by the FarmBot Genesis, designed and built at DTU Skylab as a platform for student projects, course integration, and future startup exploration.

Farmbot: https://farm.bot/
Farmbot Genesis Documentation: https://genesis.farm.bot/v1.8/assembly/intro



DTU Skylab - Gardening Robot - Seeding Sequence Testing: https://www.youtube.com/watch?v=myrVL9h8MHA 

DTU Skylab - Gardening Robot - Basic movements demo: https://www.youtube.com/watch?v=C3N4Af2INCI



\## Features



\- 4×4 modular pot grid with laser‑cut wooden puzzle frame and 3D‑printed connectors  

\- Aluminum‑extrusion CNC gantry with V‑slot X/Z and leadscrew Y‑axis  

\- Toolhead with seed dispenser, watering nozzle, peristaltic pump, and USB camera  

\- Fully automated sequence: drill hole → drop seed → cover → water  

\- Calibrated peristaltic pump with ml‑per‑mm factor  

\- Browser‑based control via Klipper + Fluidd and automation via Home Assistant  



\## Repository layout



\- `hardware/` – CAD models (.f3d), .DXF for wooden puzzle grid, and BOM (.xlsx) 

\- `electronics/` – Schematics and wiring diagrams, pictures of connections 

\- `firmware/klipper/` – `printer.cfg` and pictures of Fluidd UI 

\- `docs/` – Build guide, user guide, and notes for future improvements  

\- `pictures/` – Pictures of the assembly and 3D models


\## Hardware overview


\- Aluminum extrusion frame and V‑slot linear motion  

\- Custom metal parts (milled, lathed, laser‑/waterjet‑cut, hand‑finished)  

\- Laser‑cut 16‑pot grid mounted on 3D‑printed legs and extrusion supports  

\- NEMA17 steppers, micro servo for seed dispenser, peristaltic pump, mechanical endstops  



\## Electronics \& software



\- 1× Raspberry Pi running Klipper + Fluidd with BTT SKR Pico motion controller  

\- 1× Raspberry Pi running Home Assistant for automation  

\- Custom wiring with JST connectors and soldered harnesses  

\- Klipper configuration for axis calibration, safe homing, travel limits, and planting/watering macros  



\## Documentation



See `docs/` for:



\- Step‑by‑step build instructions - Also follow Farmbot's Genesis documentation: https://genesis.farm.bot/v1.8/assembly/intro

\- Basic operation and maintenance  

\- Ideas and guidelines for future extensions (vision, sensors, new tools)



