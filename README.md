# KY-004 Key Switch & KY-016 RGB LED with Arduino
## Components:
- Arduino (e.g., Uno, Nano)
- KY-004 Key Switch Module
- KY-016 RGB LED Module
- Jumper wires

## KY-004 Key Switch (KY-004.ino)**

### Wiring:
- **VCC** → **5V**, **GND** → **GND**, **SIG** → **Pin 2**

### Function:
- Reads HIGH when pressed, LOW when released.

For more details, check the full guide:  
[Using the Key Switch Module KY-004 with Arduino](https://www.phippselectronics.com/using-the-key-switch-module-ky-004-with-arduino/)

---

## **KY-016 RGB LED (KY-016.ino)**

### Wiring:
- **VCC** → **5V**, **GND** → **GND**, **R Pin** → **Pin 9**, **G Pin** → **Pin 10**, **B Pin** → **Pin 11**

### Function:
- Controls RGB color by adjusting Red, Green, and Blue pins.

For more details, refer to:  
[KY-016 RGB Full Color LED Module](https://arduinomodules.info/ky-016-rgb-full-color-led-module/)

---

## Usage:
1. **Connect** the modules.
2. **Upload** `KY-004.ino` and `KY-016.ino` to Arduino.
3. **Test**: Press the key switch and change LED colors.

---

## Troubleshooting:
- **No output**: Check connections.
- **LED issue**: Verify RGB wiring.

---

This version includes the links for further details and keeps the information concise.
