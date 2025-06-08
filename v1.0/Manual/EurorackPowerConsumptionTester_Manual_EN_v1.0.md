# Eurorack Power Consumption Tester Manual (English)
![EPCT_Image](../../Images/EPCT_Side.jpeg)

## Overview

**Eurorack Power Consumption Tester** is a utility jig for measuring the power consumption of modular synthesizers.  
Used in combination with a digital multimeter, it allows measurement of current draw on +5V, +12V, and -12V rails.

---

## Specifications

- **Format**: External testing tool (not a rack-mounted module)  
- **Width**: 0 HP  
- **Depth**: 10 mm  
- **Power Draw**: +12V: 0mA / -12V: 0mA (Passive)

---

## Parts List

- [Red Binding Post MB-124-N-RED](https://akizukidenshi.com/catalog/g/g114241/) ×3  
- [Black Binding Post MB-124-N-BLACK](https://akizukidenshi.com/catalog/g/g114242) ×3  
- [Resettable Fuse 0.5A (trip: 1A, 60V) MF-R050](https://akizukidenshi.com/catalog/g/g112628/) ×3  
- [3P Toggle Switch (SPDT) for panel mount](https://akizukidenshi.com/catalog/g/g103774/) ×3  
- [3mm Red LED OSR5JA3Z74A (625nm, 70°)](https://akizukidenshi.com/catalog/g/g111577/) ×3  
- [IDC Box Header 16P (2×8)](https://ja.aliexpress.com/item/1005004266492521.html) ×2  
- Chip Resistor 0603 1kΩ ×1  
- Chip Resistor 0603 2.2kΩ ×2

### Additional Required Tools

- Banana cables ×2  
- Digital multimeter ×1  
- 16P-16P IDC flat cable ×1  
- 16P-10P IDC flat cable ×1

---

## Assembly Tips

- Start with low-profile components (e.g., resistors).  
- The square pad of the LED indicates the cathode (negative).  
- When tightening the binding post nut, be careful not to scratch the solder mask, as this could short to GND.

---

## Usage Instructions

![Measurement](../../Images/EPCT_Test.jpg)

1. Ensure your Eurorack power supply is **OFF**.  
2. Connect the power supply and the tester’s **IN** header using a 16P-16P IDC cable.  
3. Set all three switches (+5V, +12V, -12V) to the **THRU** position.  
4. Connect the tester’s **OUT** to the test module via a 16P-10P cable.  
5. Power on the system. The LEDs on the tester should light up.  
6. Connect the tester’s terminals to a multimeter using banana cables, and set the multimeter to **DC current mode**.  
7. Flip each switch to the **TEST** position to route current through the multimeter and measure consumption.  
8. Apply full load to the module and record current readings.

> ⚠ **Warning**: Do **not** plug/unplug cables while power is on.  
> The designer accepts **no liability** for any damage caused by misuse of this tool.

---

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

---

## Credits

- **Designed by**: StudioKAT  
- **Website**: [https://www.studiokat.jp/](https://www.studiokat.jp/)  
- **GitHub**: [https://github.com/StudioKAT](https://github.com/StudioKAT)  
- **X (Twitter)**: [https://x.com/StudioKAT_synth](https://x.com/StudioKAT_synth)  
- **Instagram**: [https://www.instagram.com/studiokat_modular/](https://www.instagram.com/studiokat_modular/)

---

## Changelog

- `2025-04-24`: v1.0 Released  
