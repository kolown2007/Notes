
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

- MOSI - pin 23
- MISO - pin 19
- CLK - pin 18
- CS - pin 5
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


----
1. **Freesound.org** - Huge collection of CC-licensed sound effects and instrument samples [https://freesound.org/](vscode-file://vscode-app/c:/Users/Barry/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html)

2. **Free Music Archive** - Includes individual instrument sounds [https://freemusicarchive.org/](vscode-file://vscode-app/c:/Users/Barry/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html)

3. **SampleSwap** - Free sample packs [https://sampleswap.org/](vscode-file://vscode-app/c:/Users/Barry/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html)

4. **Soundbible** - Simple sound effects [https://soundbible.com/](vscode-file://vscode-app/c:/Users/Barry/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html)

5. **BBC Sound Effects** - High quality sound library [https://sound-effects.bbcrewind.co.uk/](vscode-file://vscode-app/c:/Users/Barry/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html)


### For Musical Instrument Sounds:

1. **Virtual Piano Sounds** [https://github.com/gleitz/midi-js-soundfonts](vscode-file://vscode-app/c:/Users/Barry/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html)

2. **University of Iowa Musical Instrument Samples** (academic quality) [https://theremin.mu](vscode-file://vscode-app/c:/Users/Barry/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html)

---

query sounds

https://gleitz.github.io/midi-js-soundfonts/FatBoy/accordion-mp3/A0.mp3

----
MIDI to JSON
https://tonejs.github.io/Midi/

tonejs instruments
https://nbrosowsky.github.io/tonejs-instruments/demo.html

audio files
https://github.com/Tonejs/audio



----

SD card module
https://www.electronicwings.com/esp32/microsd-card-interfacing-with-esp32

- MOSI - pin 23
- MISO - pin 19
- CLK - pin 18
- CS - pin 5