# "ESP32 BLUEDECKY" 🦆

⚠️ **DISCLAIMER** ⚠️
`FOR EDUCATIONAL PURPOSES AND CYBERSECURITY TESTING ONLY.
This project is created solely for educational purposes, security research, and testing. Unauthorized use on devices without explicit permission is strictly prohibited and illegal. The developer assumes no responsibility or liability for any misuse or damage caused by this software.`

![image](image.png)

---

### 🌟 WHAT'S NEW IN THIS UPDATE (v2.0.0)
- **Wi-Fi Admin Panel (http://192.168.4.1):** Connect to the device's Wi-Fi Access Point and access the admin panel via browser at `192.168.4.1`.
- **Automatic Keylogger:** The firmware runs an automatic keylogger in the background.
- **Custom Payload Control:** Easily customize pre-set scripts and send live commands directly through the admin panel.

---

# How It Works & Installation

🌏 **Flash Firmware:** 📥
Flash/Install the `.bin` files onto your ESP32 board using your preferred ESP flashing tool.

⚡ **Power Up:**
Flash the `.bin` code now using this web flasher:
[https://esptool.spacehuhn.com/](https://esptool.spacehuhn.com/)

---

# FLASHING INSTRUCTION

| File Name | Offset |
| :--- | :--- |
| `bootloader.bin` | `0x1000` |
| `partitions.bin` | `0x8000` |
| `firmware.bin` | `0x10000` |

---

# Features & Usage

⚙️ **1. Power & Bluetooth Connection:** 📱🔗
- Provide power supply to the ESP32 board via USB or an external battery source.
- Turn on Bluetooth on your mobile device and connect to the device named **"Bluedecky"**.

⚙️ **2. Automated Execution & Keylogger:** 🤖
- Pair your Android smartphone with the ESP32 BlueDecky (Bluetooth device name: **"Bluedecky"**).
- The device automatically executes pre-configured automated tasks on your connected device.
- Simultaneously runs background keystroke recording logic (Keylogger).

🌐 **3. Wi-Fi Admin Panel Access:** 💻
- Turn on Wi-Fi on your phone or PC and connect to the ESP32 Wi-Fi Hotspot network.
- Open any web browser and go to: **`http://192.168.4.1`**
- From the Admin Panel, you can:
  - View logged keystrokes.
  - Manage pre-set configuration scripts.
  - Send customized rubber ducky codes directly to the device.

---

# Requirements

⚙️ ESP32 Development Board  
⚙️ Power Cable / Battery Source 🔋  
⚙️ Smartphone (Android) 📱  
⚙️ Web Browser (Chrome/Firefox for accessing `192.168.4.1`)  
⚙️ IDE (Windows Working Environment)  

---

## DEVELOPER ##
`@TONIX`
