# PN532 on ESP32

Use PN532 NFC module on ESP32 with hardware SPI

Connections:

| ESP32     | PN532 module | Note                                    |
|-----------|--------------|-----------------------------------------|
| 3.3V      | 3.3V         |                                         |
| SCK (IO)  | SCK          |                                         |
| MISO (IO) | MISO         |                                         |
| MOSI (IO) | MOSI         |                                         |
| IO5       | SS           | You can change to other digital IO pins |
|           | RST          | No connection                           |
|           | IRQ          | No connection                           |



