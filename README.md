<h1 align="center">- Rogue32 Made By Zynth -</h1>
<div align="center">
  <img src="rogue32.png" align="center">
  <h3 align="center">A small and compact pentesting tool.</h3>
</div>

---

## Rogue32
The Rogue32 Is a small pentesting tool designed for portability and functionality, it offers multiple functions like:
- Wifi (Sniffers, Spamming, Evil portal)
- Bluetooth (BLE Advertise spam, Sniffer)
- nRF24 (BLE Jammer, 2.4 gHz jammer)
- PN532 ( Not yet added ) (Reading NFC and RFID cards and emulating them) (13.56 mHz)
- IR (KY-022, KY-005) (Everything IR related, scanning and emulating signals)

                                                                    
JAMMING IS ILLEGAL! JAM AT YOUR OWN RISK!!

the nRF24, Bluetooth and Wifi functions disrupt:
Bluetooth speakers, RC drones, Wifi signals, anything around 2.4gHz

---

## Hardware - Make your own Rogue32

<img src="20241117_104048-removebg.png" style="width: 25%; height:25%">

### **Required:**  
- ESP32 Dev Module (38 PIN MODULE NEEDED)
- 1.3 inch ST7789 TFT

### **Optional:**
- nRF24L01
- KY-022 + KY-005
- PN532
- TP4056 Charging Module
- 3.7V Battery





## ESP32 38 PIN + TFT + BUTTONS PINOUT
| ESP32 Pin | TFT Pin | Buttons |
|---------------|------------------|--------------------|
| 5           | CS (Can leave unconnected)             |
| 4           | RST/RES              |
| 21            | DC          |
| 23           | MOSI/SDA          |
| 18           | SCK/SCL          |
| 3v3          | VCC          |
| GND          | GND          |
| 32 | | Up Button |
| 33 | | Down Button |
| 25 | | Select Button |
| 26 | | Back Button |

## FLASHING
The files are called esp32driverv1.ino.Something
because i reused the sketch file of my old project
| OFFSET | FILE |
|---------------|------------------|
| 0x1000           | Bootloader            |
| 0x10000           | .ino.bin              |
| 0x8000            | Partitions          |




## Discord
You can join my Discord server [here](https://discord.gg/6vNKuQkG)


<h1 align="center"> DISCLAIMER </h1>

<h4 align="center">Remember, jamming is illegal, use this tool at your own risk</h4>
