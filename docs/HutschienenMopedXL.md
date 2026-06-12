# Hutschienenmoped XL



Das **Hutschienenmoped XL** ist die erweiterte Version unserer Open-Source-ECU. Es wurde speziell für die Integration in ISOBUS-Systeme entwickelt und eignet sich hervorragend für anspruchsvolle Steuerungsaufgaben in der Landtechnik.

## 🌟 Highlights

* **ISOBUS Kompatibel:** Volle Unterstützung für **ISO 11783**.
* **IEC 61499:** Vorbereitet für verteilte Steuerungssysteme.
* **Open Source:** Die Hardware ist vollständig offengelegt und zertifiziert.
* **Erweiterbar:** Durch den modularen Aufbau und die Nutzung des ESP32 kann das System flexibel angepasst werden.

---

## 🎖 Zertifizierung

Das Hutschienenmoped XL ist offiziell als Open Source Hardware zertifiziert.

* **UID:** [DE000145](https://certification.oshwa.org/de000145.html)
* **Zertifizierungsstelle:** Open Source Hardware Association (OSHWA)

[![OSHWA Certification DE000145](https://github.com/Meisterschulen-am-Ostbahnhof-Munchen/ISOBUS_Hardware/raw/master/certification-mark-DE000145-stacked.png)](https://certification.oshwa.org/de000145.html)

---

## 🛠 Konstruktion & CAD

Das Hardware-Design wird in Autodesk Fusion 360 gepflegt. Hier können Sie die aktuellen 3D-Modelle und Schaltpläne einsehen:

* 🔌 **[Hauptplatine (PCB) in Fusion 360 ansehen](https://a360.co/3YcFeBx)**
* 📦 **[Gesamtzusammenbau (Assembly) in Fusion 360 ansehen](https://a360.co/4cJ5Ajy)**

### Repository
Der Quellcode und die Hardware-Dateien liegen im GitHub-Repository:
[📂 GitHub: Hutschienenmoped-XL](https://github.com/Meisterschulen-am-Ostbahnhof-Munchen/ISOBUS_Hardware/tree/master/Hutschienenmoped-XL)

---

## 📸 Galerie

Hier einige Einblicke in die Hardware:

| Ansicht | Beschreibung |
| :--- | :--- |
| ![PCB Top](https://github.com/user-attachments/assets/383bf22e-cba5-43bd-8128-fcb774ffd311) | **Bestückte Platine (Oben)**<br>Zeigt den ESP32 und die Anschlüsse. |
| ![PCB Bottom](https://github.com/user-attachments/assets/e9367dd6-669b-4474-8874-dbe8fb007cbe) | **Bestückte Platine (Unten)**<br>Rückseite mit Leiterbahnenführung. |
| ![Case](https://github.com/Meisterschulen-am-Ostbahnhof-Munchen/ISOBUS_Hardware/assets/69573151/a77ef262-608f-44c5-9354-b3eb979526ce) | **Gehäuse-Montage**<br>Das fertige Modul im Hutschienen-Gehäuse. |

---

## ℹ️ Technische Details

* **Controller:** ESP32 (M5Stack Atom / Atom Lite kompatibel)
* **Spannungsversorgung:** 12V (Bordnetz)
* **Schnittstellen:**
    * ISOBUS (CAN)
    * WLAN / Bluetooth (via ESP32)
    * Erweiterungsports für Sensoren/Aktoren