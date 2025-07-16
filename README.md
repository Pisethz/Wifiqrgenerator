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

![Screenshot](https://private-user-images.githubusercontent.com/143471493/467204330-421addb8-cb70-4260-b4c2-1a47e3330c0e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTI2OTU4NzYsIm5iZiI6MTc1MjY5NTU3NiwicGF0aCI6Ii8xNDM0NzE0OTMvNDY3MjA0MzMwLTQyMWFkZGI4LWNiNzAtNDI2MC1iNGMyLTFhNDdlMzMzMGMwZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNzE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDcxNlQxOTUyNTZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1iNjc4NmU0ZTY5ZTUzNTIzNjFhMmQ5NTUxMjJlNTFlNTk1Nzg3MzRiZTM5Y2EwMWNiZTQwMjIxYTc4MDI5OTA3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9._Aea0_4PcXgVFGc9lP8AzBIP3A0kda_o_Gd6Wq9yEcI)
![Screenshot](https://private-user-images.githubusercontent.com/143471493/467208759-26e3abaa-1009-4f8b-95c2-816393e78656.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTI2OTYxOTMsIm5iZiI6MTc1MjY5NTg5MywicGF0aCI6Ii8xNDM0NzE0OTMvNDY3MjA4NzU5LTI2ZTNhYmFhLTEwMDktNGY4Yi05NWMyLTgxNjM5M2U3ODY1Ni5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNzE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDcxNlQxOTU4MTNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kOTlmNjE5Y2JhMWE3NzY4YjVmZWM1MDlkZTRlZjA3ZmNiYTFhYzg0NDg5MzliMDNjYjIyNTYyZjJmNjU2OGNlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.WrWkyVmYeJHXXLlqe-PEyqi9gSuqnObRgvUay1lCdGA)


---

## ⚡ Credits
- UI/UX: [Pisethz](https://github.com/Pisethz) x [JackyJackyHunt](https://github.com/Pisethz)
- QR Code: [qrcode](https://pypi.org/project/qrcode/)
- Excel: [openpyxl](https://pypi.org/project/openpyxl/)
- Word: [python-docx](https://pypi.org/project/python-docx/)

---

## 📝 License

MIT License. See [LICENSE](LICENSE) for details.
