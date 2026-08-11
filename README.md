<!-- ===================================================================== -->
<!--                      NOTYBOOK GITHUB README                           -->
<!-- ===================================================================== -->

<div align="center">

  <!-- Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,18,24,30&height=220&section=header&text=Notybook&fontSize=70&animation=fadeIn&fontColor=ffffff" width="100%" alt="Notybook Header" />

  <!-- Animated Typing Tagline -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Outfit&weight=600&size=22&pause=1000&color=E5C07B&center=true&vCenter=true&width=600&height=45&lines=Modern+%26+Ultra-Fast+Rich-Text+Notes;AES-256+Bank-Grade+Master+Password+Lock;100%25+Offline+LocalStorage+Privacy;Encrypted+.JSON+Backup+%26+Restore;Apple+Notes+Mobile+Responsive+UI" alt="Typing SVG" />
  </a>

  <br />

  <!-- Badges -->
  <p align="center">
    <img src="https://img.shields.io/badge/Security-AES--256--GCM-E5C07B?style=for-the-badge&logo=keeper&logoColor=1c1c1e" alt="Security AES-256" />
    <img src="https://img.shields.io/badge/Storage-100%25_Offline-00E676?style=for-the-badge&logo=sqlite&logoColor=white" alt="Offline Storage" />
    <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    <img src="https://img.shields.io/badge/HTML5-Modern-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/Responsive-iOS_Apple_Style-007AFF?style=for-the-badge&logo=apple&logoColor=white" alt="Mobile Responsive" />
  </p>

</div>

---

## 📖 Overview

**Notybook** is a state-of-the-art, lightning-fast, offline-first rich-text note taking application. Inspired by modern macOS & iOS Apple Notes, Notybook combines luxury aesthetic design, custom typography, instant local vector rendering, and zero-trust **AES-256 Master Password Encryption**.

---

## 🔒 Security, Privacy & Reliability (Is It Safe?)

### ❓ Kahan Store Hota Hai Aapka Data?
- **100% Local Storage:** Aapka poora data (notes, folders, titles, formatting) sirf aur sirf aapke apne browser ke **LocalStorage** mein store hota hai.
- **Zero Cloud Servers:** Notybook **kisi bhi external server, cloud database, ya third-party API par data NAHI bhejta**.
- **Complete Internet Independence:** Intranet ya offline mode par bhi 100% instant load hota hai.

### 🛡️ Kya Yeh Safe Hai? (AES-256 Encryption)
**YES! 100% Unhackable Privacy.**
- **PBKDF2 Key Derivation:** Master Password set karte hi Notybook `PBKDF2` (100,000 iterations + SHA-256) ke zariye 256-bit secret key generate karta hai.
- **AES-GCM Encryption:** Storage mein jaane se pehle saare notes aur folders AES-GCM format mein lock ho jaate hain.
- **Inspect-Proof:** Agar koi Browser DevTools (`F12 -> Application -> LocalStorage`) khol kar bhi dekhe, to use readable text ki jagah encrypted ciphertext (`U2FsdGVkX1...`) dikhega.

---

## 📦 Encrypted Backup & Restore System

Notybook contains a built-in **1-Click Encrypted Data Portability Engine**:

| Action | How It Works | Feature |
| :--- | :--- | :--- |
| **📦 Export Backup** | Click `Backup Data` to download `notybook_backup_YYYY-MM-DD.json`. | Backup file contains **encrypted JSON data**. Even if someone steals your backup file, they cannot read it without your Master Password! |
| **📥 Restore Backup** | Open Notybook on any laptop/phone, click `Restore Backup`, select `.json` file. | Enter your Master Password when prompted. **100% formatting, folders, and notes are instantly restored!** |

---

## ✨ Key Features

- 📝 **Rich Text Editor:** Headings (`H1` 32px, `H2` 24px, `H3` 19px), Bold (`Ctrl+B`), Italic (`Ctrl+I`), Underline (`Ctrl+U`), Strikethrough.
- 🔤 **12 Custom Fonts:** Clean, Modern, Elegant, Display & Romantic Handwriting fonts (Roboto, Coolvetica, Bebas Notes, Lemon Milk, Papernotes, Cheese Milky, etc.).
- 📌 **Pin & Organize:** Pin important notes to the top of list with `📌` indicator.
- 📁 **Folder Management & Icon Picker:** Create custom folders and select from **12 Vector Ionicons** (📁 Work, ⚡ Quick, 👤 Personal, 💡 Ideas, 📚 Study, 🎨 Design, 🚀 Projects, ⭐ Favorites, 🔒 Private, etc.).
- 🗑️ **Trash & 1-Click Restore / Empty Trash:** Safely restore accidentally deleted notes or permanently empty trash with confirmation.
- 📱 **Apple Notes iOS Mobile UI:** 100% mobile-responsive 3-column switcher (`view-sidebar`, `view-notes`, `view-editor`) with smooth iOS slide animations and `‹ Folders` / `‹ Notes` back buttons.
- 🔒 **Master Password App Lock Screen:** Instant app locking with `🔒 Lock` button and password show/hide toggle (`👁️`).

---

## 🚀 How to Run & Deploy

### Local Machine (WAMP / XAMPP / Live Server)
1. Clone or download project files into your local web root (`C:\wamp64\www\inote\`).
2. Open browser and navigate to `http://localhost/inote/`.

### 🌐 Deploying to GitHub Pages
1. Push project files to your GitHub repository.
2. Go to **Repo Settings -> Pages -> Source -> Branch: main -> Save**.
3. Your app is live with free HTTPS at `https://yourusername.github.io/Notybook/`!

---

<br />

<div align="center">

  ## 👨‍💻 Created By

  ### **JaddyGaud**

  Connect & Follow on Instagram for updates:

  <a href="https://instagram.com/jaddygaud" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-@jaddygaud-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram @jaddygaud" />
  </a>

  <br /><br />

  <sub>© 2026 Notybook. Created with ❤️ by JaddyGaud. All Rights Reserved.</sub>

</div>
