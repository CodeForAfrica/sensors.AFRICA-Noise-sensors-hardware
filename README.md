# sensors.AFRICA Noise Sensor Kits Hardware


## Tools used

* Autodesk Eagle

* Fusion360


## sensors.AFRICA Stack

1. Firmware - https://github.com/CodeForAfrica/sensors.AFRICA-Noise-sensors-software
2. API - https://github.com/CodeForAfricaLabs/sensors.AFRICA-AQ-api
3. Map - https://github.com/CodeForAfrica/sensors.AFRICA-AQ-map-v2


## Documentation

Latest PCB Design on](https://a360.co/4bMNexy) Fusion360

*Front layer*
![Front layer](/images/noise-sensor-front.png) 

*Back layer*
![Back layer](/images/noise-sensor-back.png)

### Pinout 
- **RX** and **TX** pins on the ESP-12 to communicate to the GSM are **0** and **2** respectively.
- The **GSM RESET** pin is **NOT** physically connected to the ESP module.

## License

GNU General Public License v3.0

sensors.AFRICA is a citizen-science focused project by Code for Africa that seeks to address data gaps by providing low cost sensors, which people can use to measure and monitor the quality of the air, water, and environment in their communities. This web app seeks to be the public portal through which most users would discover and explore the data and intiative.

Copyright (C) 2022 Code for Africa

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <https://www.gnu.org/licenses/>
