# Rotary_encoder_lite

Reads the position of a rotary encoder and outputs it with a simple function.
This is a copy of the [original library](https://github.com/Bendeguz-Cs/Rotary_encoder/tree/main) and will regulary receive all of the base functionality updates.

## Description

Simple Arduino library used to read the position of an incremental rotary encoder.

## Hardware

Recommended hardware debouncing using a 10 KΩ resistor between the MCU pin and the CLK pin of the encoder(the pin defined first in the initialization) and a 100nF(0.1μF) capacitor between the MCU pin and GND. See below.

> [!NOTE]
> The KY-040 has the resistors built in, you don't need to add external ones

<img width="500" height="480" alt="image" src="https://github.com/user-attachments/assets/a9f15062-2125-424d-ad24-a0ce12119c01" />

---

<details><summary>Compatibility</summary>
<p>

This library is compatible with **AVR** and all other **MCU**s that have **Hardware interrupts**.
The library was tested on:

- Arduino NANO

- Arduino UNO R3

- Arduino UNO R4 MINIMA

- Arduino UNO R4 WiFi

- Seeeduino XIAO SAMD21

- Seeeduino XIAO ESP32-S3

</p>
</details>


## License
MIT License
