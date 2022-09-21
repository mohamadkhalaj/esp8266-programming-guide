# Esp8266 programming guide
For programming your ESP8266 with arduino, connect pins like this:
### ESP8266 | Arduino
(ESP left and arduino right)
```
TX -> TX
RX -> RX

IO0 -> Gnd
GND -> Gnd

RST -> 3.3V
VCC -> 3.3V
EN -> 3.3v
```
and in arduino do:
```
RESET -> GND
```
which tells arduino to just program ESP not arduino!

# Normal mode
Just remove IO0 from Gnd and re-plug ESP's VCC or only connect VCC and GND to arduino!
