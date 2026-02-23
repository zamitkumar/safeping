# safeping
emergency-qr

> **Your emergency info, encoded directly inside a QR code. No server. No internet. No app needed.**

![SafePing Banner](https://img.shields.io/badge/SafePing-Emergency%20QR-ff4757?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyek0xMyAxN2gtMnYtNmgydjZ6bTAtOGgtMlY3aDJ2MnoiLz48L3N2Zz4=)
![No Server](https://img.shields.io/badge/No%20Server-100%25%20Offline-2ed573?style=for-the-badge)
![Single File](https://img.shields.io/badge/Single%20HTML%20File-No%20Install-1e90ff?style=for-the-badge)

---

## 🌟 What is SafePing?

SafePing is a **single HTML file** that generates emergency contact QR codes. All your personal and medical data is encoded **directly inside the QR code image** — nothing is sent to any server, nothing is stored in the cloud.

When someone scans your QR code (police, paramedic, bystander), a **fully working emergency card opens instantly on their phone** — even with no internet connection.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🌐 **Public QR** | Shows name, blood type, allergies. Phone numbers are **scrambled visually** but callable with one tap |
| 🔒 **Private QR** | Full medical profile (medications, conditions, doctor). Protected by a **PIN code** |
| 📴 **100% Offline** | All data lives inside the QR image — no server, no database, no internet needed |
| 🖨️ **Print & Go** | Download QR as PNG and print it — stick on helmet, wallet, bike, ID card |
| 🔐 **PIN Protection** | Private QR requires a PIN before revealing medical details |
| 📞 **One-Tap Call** | Tap the button → phone dials instantly, no number to remember or type |
| 🩸 **Medical Info** | Blood type, allergies, medications, conditions, doctor all in one place |

---

## 🚀 How to Use

### Step 1 — Open the App
Just open `emergency-qr-app.html` in any browser (Chrome, Firefox, Safari). No installation needed.

### Step 2 — Fill in Your Details
- Your name, date of birth, blood type, allergies
- Emergency contact names and phone numbers
- Medications, medical conditions, doctor info

### Step 3 — Set a PIN
Choose a 4–8 digit PIN to protect your Private QR code.

### Step 4 — Generate
Click **⚡ Generate QR Codes** — two QR codes are created instantly.

### Step 5 — Download & Print
- **Public QR** → Print and stick on your helmet, bike, wallet, medical bracelet
- **Private QR** → Give to your doctor or keep in your medical file

---

## 🔒 Privacy & Security

- ✅ **Zero data transmission** — nothing leaves your device
- ✅ **No accounts, no login, no tracking**
- ✅ **Phone numbers scrambled** on the public card (e.g. `+491 ●●●●● 67`)
- ✅ **PIN-gated** private profile — medical details never exposed publicly
- ✅ **Works offline** — the QR encodes a complete self-contained HTML page
- ⚠️ The PIN uses a simple hash for obfuscation. This is not military-grade encryption — do not store highly sensitive data.

---

## 📱 Use Cases

- 🚴 **Cyclists & motorcyclists** — stick Public QR on helmet
- 🏃 **Runners & hikers** — put on sports watch strap or water bottle
- 🧓 **Elderly care** — print and laminate for wallet or lanyard
- 🏥 **Medical conditions** — diabetes, heart conditions, epilepsy
- 🧒 **Children** — school bag tag with parent contact
- ✈️ **Travelling abroad** — local responders can scan without language barrier

---

## 📁 Project Structure

```
safeping/
├── emergency-qr-app.html   ← The entire app (single file)
└── README.md               ← This file
```

That's it. One file. No dependencies to install. No build process.

---

## 🛠️ Tech Stack

- Pure **HTML + CSS + JavaScript** — no frameworks
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) — QR generation (loaded from CDN)
- [Google Fonts](https://fonts.google.com) — Space Grotesk + JetBrains Mono
- Data URI encoding — embeds the entire emergency page inside the QR

---

## 🌐 Deploy on GitHub Pages (Optional)

If you want a shareable online link:

1. Rename `emergency-qr-app.html` → `index.html`
2. Go to your repo **Settings → Pages**
3. Set Source: `main` branch, `/ (root)` folder
4. Your app will be live at: `https://YOUR-USERNAME.github.io/safeping/`

---

## 🤝 Contributing

Pull requests welcome! Ideas for improvement:

- [ ] Multiple language support
- [ ] Custom QR colors / logo overlay
- [ ] vCard / NFC export
- [ ] Printable card template (wallet-sized)
- [ ] Dark/light theme toggle

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## ⚠️ Disclaimer

SafePing is a personal safety tool, not a medical device. Always carry official medical ID if you have serious conditions. The PIN protection is basic obfuscation — do not rely on it for highly sensitive data.

---

<p align="center">Made with ❤️ for personal safety · <a href="https://github.com/zamitkumar/safeping">zamitkumar/safeping</a></p>
