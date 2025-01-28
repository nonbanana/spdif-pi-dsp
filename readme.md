## reference
- https://github.com/elehobica/pico_spdif_rx

## device
- raspberry pi pico (rp2040)
- toslink rx module
- raspberry pi (tested  4 but any one will be OK)

## pin assignment
### raspberry pi <-> raspberry pi pico
|pi pin|description|pico pin|description|
|--|--|--|--|
|1|3V3|39|VSYS|
|9|GND|28|GND|
|12|GPIO 18 (BCK)|21|GPIO 15|
|35|GPIO 19 (LRCK)|22|GPIO 17|
|38|GPIO 20 (DIN)|24|GPIO 18|

### raspberry pi pico <-> TOSLINK rx module
|TOSLINK pin|description|pico pin|description|
|--|--|--|--|
|1|Vout|20|GPIO 15|
|2|GND|18|GND|
|3|Vcc|36|3V3(OUT)|
