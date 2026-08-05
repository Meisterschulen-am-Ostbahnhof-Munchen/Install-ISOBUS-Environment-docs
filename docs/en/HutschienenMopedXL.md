# DIN Rail Moped XL
The **DIN Rail Moped XL** is the enhanced version of our open-source ECU. It was specifically developed for integration into ISOBUS systems and is ideally suited for demanding control tasks in agricultural machinery.
## 🌟 Highlights
* **ISOBUS Compatible:** Full support for **ISO 11783**.
* **IEC 61499:** Prepared for distributed control systems.
* **Open Source:** The hardware is fully disclosed and certified.
* **Expandable:** Thanks to its modular design and the use of the ESP32, the system can be flexibly adapted.

---

## 🎖 Certification

The DIN Rail Moped XL is officially certified as open-source hardware.

* **UID:** [DE000145](https://certification.oshwa.org/de000145.html)
* **Certification Authority:** Open Source Hardware Association (OSHWA)

[![OSHWA Certification DE000145](https://github.com/Meisterschulen-am-Ostbahnhof-Munchen/ISOBUS_Hardware/raw/master/certification-mark-DE000145-stacked.png)](https://certification.oshwa.org/de000145.html)

---

## 🛠 Design & CAD

Hardware design is maintained in Autodesk Fusion 360. Here you can view the current 3D models and schematics:

* 🔌 **[View mainboard (PCB) in Fusion 360 ](https://a360.co/3YcFeBx)**
* 📦 **[View complete assembly in Fusion 360 ](https://a360.co/4cJ5Ajy)**

### Repository
The source code and hardware files are located in the GitHub repository:

[📂 GitHub: DINschienenmoped-XL ](https://github.com/Meisterschulen-am-Ostbahnhof-Munchen/ISOBUS_Hardware/tree/master/Hutschienenmoped-XL)

---

## 📸 Gallery

Here are some insights into the hardware:

| View | Description |
| :--- | :--- |
| ![PCB Top](https://github.com/user-attachments/assets/383bf22e-cba5-43bd-8128-fcb774ffd311) | **Assembled PCB (Top)** <br> Shows the ESP32 and its connections. |
| ![PCB Bottom](https://github.com/user-attachments/assets/e9367dd6-669b-4474-8874-dbe8fb007cbe) | **Assembled PCB (Bottom)** <br> Back side with trace layout. |
| ![Case](https://github.com/Meisterschulen-am-Ostbahnhof-Munchen/ISOBUS_Hardware/assets/69573151/a77ef262-608f-44c5-9354-b3eb979526ce) | **Enclosure Assembly** <br> The finished module in a DIN rail enclosure. |

---

## ℹ️ Technical Details
* **Controller:** ESP32 (M5Stack Atom / Atom Lite compatible)
* **Power Supply:** 12V (vehicle electrical system)
* **Interfaces:**
* ISOBUS (CAN)
* Wi-Fi / Bluetooth (via ESP32)
* Expansion ports for sensors/actuators

---

### 🌐 Related topics on ms-muc-docs.de
* [🌐 ESP32 & ESP32-S3 DevKit on ms-muc-docs.de](https://www.ms-muc-docs.de/elektrotechnik/mikroelektronik/esp32/esp32-s3-devkit/)
* [🌐 PCB Design & Assembly on ms-muc-docs.de](https://www.ms-muc-docs.de/elektrotechnik/leiterplatten/bestückung/)

