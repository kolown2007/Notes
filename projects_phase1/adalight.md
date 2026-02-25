https://github.com/dmadison/Adalight-FastLED

Adalight is a simple protocol (a packet format) — not a program you install. To use it you need two things running at the same time:

- a receiver running on the microcontroller (ESP32 / Arduino) that understands the Adalight packet and writes pixels to the LED strip (this is code you upload to the board), and
- a sender on the PC/browser (Processing, p5.js, Python, Node, Web Serial, …) that samples your canvas/animation, packs the RGB bytes into the Adalight packet, and sends them over serial (USB) or network.