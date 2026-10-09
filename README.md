# AmbiScout
A portable environment sensor to sense ambient temperature, humidity, light, movement speed, and more!

Inspired by features on the Starbie, but extended for functionality and development time. 

Living in a place where the climate constantly fluctuates, it can be handy to glance at a small device that's 
not a phone to see what's happening in the air around oneself.

<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/6c1c1373-92ab-4695-aa3a-bbbb6e39c246" />

Here's some of the planned features:

- [x] Temperature Sensor
- [x] Humidity Sensor
- [ ] Battery Powered or Rechargeability
- [ ] OLED Display
- [ ] Navigation Buttons
- [ ] Power/Charging LED
- [x] Ambient Light Level Monitor
- [ ] Audio Sensor

With enough work, it might be reasonable to add in these features too, but they're lower Priority:

* Wi-Fi Connection
* Bluetooth Compatiblitiy
* Access to Weather Forcasts
* Push Notifications when Major Changes Occue


**Hardware Specifications**

* Espressif ESP32-S2 - Chosen due to high pin number, Wi-Fi and Bluetooth connectivity, compatibility with Arduino, and low cost for the given performance
  * Pin Layout Reference: https://docs.espressif.com/projects/esp-idf/en/v5.0-beta1/esp32s2/hw-reference/esp32s2/user-guide-devkitm-1-v1.html
* Light Dependent Resistor A1050 14 - Selected due to native support in KiCad and high sensitivity
  * Pin Reference: https://www.caretxdigital.com/cat6-ethernet-cable-amazon/
* I2C Temperature & Humidity Sensor - Chosen due to accuracy and multifunctionality
 * Pin Reference: https://www.alldatasheet.com/datasheet-pdf/view/1522466/SENSIRION/SHT31-DIS.html
