# AmbiScout
A portable environment sensor to sense ambient temperature, humidity, light, movement speed, and more!

Inspired by features on the Starbie, but extended for functionality and development time. 

Living in a place where the climate constantly fluctuates, it can be handy to glance at a small device that's 
not a phone to see what's happening in the air around oneself.

<img width="1125" height="746" alt="image" src="https://github.com/user-attachments/assets/758feeee-9429-4aa0-8aee-e197fa31aee8" />

Here's some of the planned features:

- [x] Temperature Sensor
- [x] Humidity Sensor
- [x] Battery Powered or Rechargeability
- [x] OLED Display
- [x] Navigation Buttons
- [x] Power/Charging Indicator
- [x] Ambient Light Level Monitor
- [x] Audio Sensor

Checks does not mean it's programmed, just accounted for and wired.

With enough work, it might be reasonable to add in these features too, but they are lower priority:

- [ ] Wi-Fi Connection
- [ ] Bluetooth Compatiblitiy
- [ ] Access to Weather Forcasts
- [ ] Push Notifications when Major Changes Occue
- [ ] Charging & Battery Info


**Hardware Specifications**

* Espressif ESP32-S3-MINI-1-N8 - Chosen due to high pin number, Wi-Fi and Bluetooth connectivity, compatibility with Arduino, and low cost for the given performance
  * Pin Layout Reference: https://documentation.espressif.com/esp32-s3-mini-1_mini-1u_datasheet_en.html
* Light Dependent Resistor A1050 14 - Selected due to native support in KiCad and high sensitivity
  * Pin Reference: https://www.caretxdigital.com/cat6-ethernet-cable-amazon/
* I2C SHT31-DIS Temperature & Humidity Sensor - Chosen due to accuracy and multifunctionality
  * Pin Reference: https://www.alldatasheet.com/datasheet-pdf/view/1522466/SENSIRION/SHT31-DIS.html
* I2S SPH0645LM4H Sound Sensor - Chosen for compactness and price point
  * Pin Reference: https://probots.co.in/technical_data/SPH0645LM4H_Datasheet.pdf
