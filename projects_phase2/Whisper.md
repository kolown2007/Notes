
- Max98357 I2S Audio Amplifier Module No Filter Class D Amplification Support ESP32 Raspberry pi
- ESP32
- https://github.com/pschatzmann/arduino-audio-tools
- https://www.youtube.com/watch?v=a936wNgtcRA
-


In this project we will use 
- **ESP32**, 
- **Max98357 12S Audio Amplifier**, 
- **horn speaker** 20 watts, 8ohms
- 5V battery + solar panel

arduino horn speaker setup
https://www.youtube.com/watch?v=K8-GgakdvCM


---
esp32 to AM radio
https://bitluni.net/am-radio-transmitter

---
![diagram](https://circuitdigest.com/sites/default/files/circuitdiagram_mic/Interface-MAX98357A-I2S-Module-with-ESP32.png)

LRC - gpio26 --> 
BCLK - gpio27 -->p27
DIN - gpio25 --> 

![esp32](https://www.upesy.com/cdn/shop/files/doc-esp32-pinout-reference-wroom-devkit.png?width=1038)


![px](https://wiki.geekworm.com/images/thumb/3/30/NodeMCU-Specification.jpg/600px-NodeMCU-Specification.jpg)


----
https://strudel.cc/workshop/first-sounds/

this lib works
https://github.com/schreibfaul1/ESP32-audioI2S


---
wiring

- MAX98357 BCLK → ESP32 GPIO 26- 10th right

- MAX98357 DIN → ESP32 GPIO 25 -11th right from top

- - MAX98357 LRC → ESP32 GPIO 22 - 3rd left button
- 


---
https://github.com/Edzelf/ESP32-Radio

https://dronebotworkshop.com/esp32-i2s/


ESP-ADF
https://github.com/espressif/esp-adf

https://docs.espressif.com/projects/esp-adf/en/latest/


Mozzi
https://github.com/sensorium/Mozzi


