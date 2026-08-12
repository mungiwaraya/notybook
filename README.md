<!-- ===================================================================== -->
<!--                      NOTYBOOK GITHUB README                           -->
<!-- ===================================================================== -->

<div align="center">

  <!-- Dynamic Animated Header Banner (Heading Unchanged) -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,10,24,30&height=250&section=header&text=Notybook&fontSize=80&animation=twinkling&fontColor=ffffff&desc=Modern%20%26%20Ultra-Fast%20Encrypted%20Rich-Text%20Notes&descSize=20&descAlignY=75" width="100%" alt="Notybook Header" />

  <!-- Animated Typing Tagline -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Outfit&weight=600&size=22&pause=1000&color=E5C07B&center=true&vCenter=true&width=600&height=45&lines=Modern+%26+Ultra-Fast+Rich-Text+Notes;AES-256+Bank-Grade+Master+Password+Lock;Encrypted+LocalStorage+Privacy;Encrypted+.JSON+Backup+%26+Restore;Apple+Notes+Mobile+Responsive+UI" alt="Typing SVG" />
  </a>

  <br />

  <!-- Badges -->
  <p align="center">
    <img src="https://img.shields.io/badge/Security-AES--256--GCM-E5C07B?style=for-the-badge&logo=keeper&logoColor=1c1c1e" alt="Security AES-256" />
    <img src="https://img.shields.io/badge/Privacy-Encrypted_LocalStorage-00E676?style=for-the-badge&logo=shieldcheck&logoColor=white" alt="Encrypted Storage" />
    <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    <img src="https://img.shields.io/badge/HTML5-Modern-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/Responsive-iOS_Apple_Style-007AFF?style=for-the-badge&logo=apple&logoColor=white" alt="Mobile Responsive" />
  </p>

</div>

---

<!-- Dynamic Animated Section Wave Backgrounds -->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,18,24,30&height=60&section=header&text=📖%20Overview&fontSize=26&animation=fadeIn&fontColor=E5C07B" width="100%" alt="Overview Banner" />
</div>

<br />

**Notybook** is a state-of-the-art, lightning-fast, secure rich-text note taking application. Inspired by modern macOS & iOS Apple Notes, Notybook combines luxury aesthetic design, custom typography, instant local vector rendering, and zero-trust **AES-256 Master Password Encryption**.

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,18,24,30&height=60&section=header&text=🔒%20Security,%20Privacy%20%26%20Reliability&fontSize=26&animation=fadeIn&fontColor=E5C07B" width="100%" alt="Security Banner" />
</div>

<br />

### ❓ Kahan Store Hota Hai Aapka Data?
- **LocalStorage Encryption:** Aapka poora data (notes, folders, titles, formatting) browser ke **LocalStorage** mein encrypted store hota hai.
- **Zero Cloud Servers:** Notybook **kisi bhi external server, cloud database, ya third-party API par data NAHI bhejta**.

### 🛡️ Kya Yeh Safe Hai? (AES-256 Encryption)
**YES! 100% Unhackable Privacy.**
- **PBKDF2 Key Derivation:** Master Password set karte hi Notybook `PBKDF2` (100,000 iterations + SHA-256) ke zariye 256-bit secret key generate karta hai.
- **AES-GCM Encryption:** Storage mein jaane se pehle saare notes aur folders AES-GCM format mein lock ho jaate hain.
- **Inspect-Proof:** Agar koi Browser DevTools (`F12 -> Application -> LocalStorage`) khol kar bhi dekhe, to use readable text ki jagah encrypted ciphertext (`U2FsdGVkX1...`) dikhega.

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,18,24,30&height=60&section=header&text=📦%20Encrypted%20Backup%20%26%20Restore%20System&fontSize=26&animation=fadeIn&fontColor=E5C07B" width="100%" alt="Backup System Banner" />
</div>

<br />

Notybook contains a built-in **1-Click Encrypted Data Portability Engine**:

| Action | How It Works | Feature |
| :--- | :--- | :--- |
| **📦 Export Backup** | Click `Backup Data` to download `notybook_backup_YYYY-MM-DD.json`. | Backup file contains **encrypted JSON data**. Even if someone steals your backup file, they cannot read it without your Master Password! |
| **📥 Restore Backup** | Open Notybook on any laptop/phone, click `Restore Backup`, select `.json` file. | Enter your Master Password when prompted. **100% formatting, folders, and notes are instantly restored!** |

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,18,24,30&height=60&section=header&text=✨%20Key%20Features&fontSize=26&animation=fadeIn&fontColor=E5C07B" width="100%" alt="Features Banner" />
</div>

<br />

- 📝 **Rich Text Editor:** Headings (`H1` 32px, `H2` 24px, `H3` 19px), Bold (`Ctrl+B`), Italic (`Ctrl+I`), Underline (`Ctrl+U`), Strikethrough.
- 🔤 **12 Custom Fonts:** Clean, Modern, Elegant, Display & Romantic Handwriting fonts (Roboto, Coolvetica, Bebas Notes, Lemon Milk, Papernotes, Cheese Milky, etc.).
- 📌 **Pin & Organize:** Pin important notes to the top of list with `📌` indicator.
- 📁 **Folder Management & Icon Picker:** Create custom folders and select from **12 Vector Ionicons** (📁 Work, ⚡ Quick, 👤 Personal, 💡 Ideas, 📚 Study, 🎨 Design, 🚀 Projects, ⭐ Favorites, 🔒 Private, etc.).
- 🗑️ **Trash & 1-Click Restore / Empty Trash:** Safely restore accidentally deleted notes or permanently empty trash with confirmation.
- 📱 **Apple Notes iOS Mobile UI:** 100% mobile-responsive 3-column switcher (`view-sidebar`, `view-notes`, `view-editor`) with smooth iOS slide animations and `‹ Folders` / `‹ Notes` back buttons.
- 🔒 **Master Password App Lock Screen:** Instant app locking with `🔒 Lock` button and password show/hide toggle (`👁️`).
- 🔑 **Change Master Password Engine:** Seamless password changing modal with previous password verification, new password confirmation, and automatic AES-256 data re-encryption.
- 🎯 **Real-Time Active Format Toolbar Syncing:** Automatic cursor tracking via `selectionchange` highlights active tools (Bold, Italic, Underline, Strikethrough, Lists) with gold accent color and updates the Heading selector (`H1`, `H2`, `H3`, `Body Text`) dynamically.
- 🚀 **Interactive Feature Showcase Notes:** Built-in default sample guide notes for new users demonstrating rich text formatting, 12 custom fonts, security guide, folder organization, vector icons, search, and keyboard shortcuts.

---

<br />

<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,18,24,30&height=120&section=footer&text=👨‍💻%20Created%20By%20JaddyGaud&fontSize=24&animation=twinkling&fontColor=ffffff" width="100%" alt="Footer Banner" />

  <br /><br />

  Connect & Follow on Instagram for updates:

  <a href="https://instagram.com/jaddygaud" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-@jaddygaud-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram @jaddygaud" />
  </a>

  <br /><br />

  <sub>© 2026 Notybook. Created with ❤️ by JaddyGaud. All Rights Reserved.</sub>

</div>
