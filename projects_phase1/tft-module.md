
## architecture

api --> esp32 --> LVGL--->screen

----
UI libraries

- **LVGL (Light and Versatile Graphics Library)**

---
Wiring

https://www.makerguides.com/interface-tft-st7735-display-with-esp32/


![wiring](https://www.makerguides.com/wp-content/uploads/2025/01/image-60.png)

| Display    | ESP32 |
| ---------- | ----- |
| CS / SS    | 5     |
| RST        | 16    |
| DC         | 17    |
| SDA / MOSI | 23    |
| SCL / SCLK | 18    |
| BKL/BL     | 22    |
| GND        | GND   |
| VCC        | 3.3V  |

