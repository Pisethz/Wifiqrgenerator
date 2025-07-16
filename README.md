```
______ _          _   _                             _    _ _ _  
| ___ (_)        | | | |                           | |  (_) | | 
| |_/ /_ ___  ___| |_| |__  ____  _ __   ___    ___| | ___| | | 
|  __/| / __|/ _ \ __| '_ \|_  / | '_ \ / _ \  / __| |/ / | | | 
| |   | \__ \  __/ |_| | | |/ /  | | | | (_) | \__ \   <| | | | 
\_|   |_|___/\___|\__|_| |_/___| |_| |_|\___/  |___/_|\_\_|_|_|                                         
```
# 🚀 WifiQRGenerator

![WiFi QR Generator](https://img.shields.io/badge/WiFi-QR%20Generator-blueviolet?style=for-the-badge&logo=wifi)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> **Generate, export, and visualize all your Windows WiFi passwords and QR codes in style!**

---

## ✨ Features
- 🔍 **Auto-detects all saved WiFi networks** on your Windows machine
- 🔑 **Extracts passwords** (admin required)
- 📦 **Exports** to TXT, Excel, Word, and a beautiful HTML dashboard
- 📱 **Generates QR codes** for instant WiFi sharing
- 🖼️ **Modern, responsive HTML UI** with search and modal QR previews
- 💾 **All exports saved in a single folder** for easy access

---

## 🛠️ Requirements
- Python 3.8+
- Windows OS (uses `netsh`)
- Admin privileges (for password extraction)
- Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚦 Usage

1. **Clone the repo:**
   ```bash
   git clone https://github.com/Pisethz/WifiQRGenerator
   cd WifiQRGenerator
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the script as administrator:**
   ```bash
   python wifi.py
   ```
4. **View your exports:**
   - Check the `wifi_exports/` folder for TXT, Excel, Word, and QR PNGs
   - The HTML dashboard will open automatically in your browser

---

## 📂 Output Example

- `wifi_exports/wifi_passwords.txt`  
- `wifi_exports/wifi_passwords.xlsx`  
- `wifi_exports/wifi_passwords.docx`  
- `wifi_exports/wifi_passwords.html`  
- `wifi_exports/wifi_qr_<SSID>.png`

---

## 🖼️ Screenshot

![Screenshot](https://user-images.githubusercontent.com/placeholder/your-screenshot.png)

---

## ⚡ Credits
- UI/UX: [Pisethz](https://github.com/yourprofile) x [JackyJackyHunt](https://github.com/yourprofile)
- QR Code: [qrcode](https://pypi.org/project/qrcode/)
- Excel: [openpyxl](https://pypi.org/project/openpyxl/)
- Word: [python-docx](https://pypi.org/project/python-docx/)

---

## 📝 License

MIT License. See [LICENSE](LICENSE) for details.
