# ESP-POE-2RL
ESP32 based board with PoE, temperature/humidity sensor, and two relays. To be used for controlling loads that cannot be commanded from the main cabinet, like for example when you need a dry contact close to some equipment or appliance. The PoE power source avoids the need for additional cabling. In external control cabinets the temperature/humidity sensor will give an indication of the environment that can be adjusted switching a heater element of a fan.

A case is also available for 3D printing.

![alt text](https://github.com/thermseekr/esp-poe-2rl/blob/main/V1/esp-poe-2rl-V1.4.0.png "ESP-POE-2RL")

## VERSION HISTORY

ESP-POE-2RL V1.4 - 2026/06/10 - Terminal blocks replaced for 3.5mm pitch. Board decreased 8mm in length. LAN8710A rotated for shorter traces. Pull-up resistor for MDIO adjusted from 2.2k to 1.5k as suggested in the datasheet. Bulk and decoupling capacitor sizes and types adjusted for better performance. Deleted temperature sensor.

ESP-POE-2RL V1.3 - 2025/06/29 - Layers reordered and board fully rerouted for better signal integrity.

ESP-POE-2RL V1.2 - 2024/12/07 - Connectors adjusted for best fitting the case.

ESP-POE-2RL V1.1 - 2024/11/29 - Initial release.

## LICENSE

This project is licensed under the [Creative Commons BY-NC 4.0 License](https://creativecommons.org/licenses/by-nc/4.0/).
Commercial use is not permitted without prior written consent. See the [LICENSE.txt](LICENSE.txt) file for details.
