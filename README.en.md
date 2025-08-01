# PPT-ADDIN-MANAGER

![GitHub release (latest by date)](https://img.shields.io/github/v/release/Tangui-Gouirand/PPT-ADDIN-MANAGER?label=version&color=blue)

📘 [Lire en français](README.md)

**PPT-ADDIN-MANAGER** is a **centralized manager for PowerPoint add-ins**.  
It allows users to **manually configure GitHub folders** containing their add-ins, then **download, install, uninstall, and update** them through a simple interface, with built-in **digital signature verification** to ensure integrity.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a3ba853d-008e-47cc-b695-501a1d8b6d66" width="400"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ece29652-88d0-4f90-b475-a3fd01bd7ff9" width="300"/>
</p>

---

## ✨ Key Features

- 📁 **Manual configuration** of GitHub folders containing add-ins
- ✅ **Automatic version checking** using GitHub Releases
- 🔘 **One-click update**: a button appears when a new version is detected
- 🧹 **Clean uninstallation** of selected add-ins
- 🔒 **Signature verification** before any installation or update

---

## 📦 Installation

1. Download the latest version from the [Releases](https://github.com/Tangui-Gouirand/PPT-ADDIN-MANAGER/releases) section.
2. Launch the `PPTAddinManager.exe` executable.
3. On first launch, the app will automatically copy itself to:  
   `C:\Users\<User>\AppData\Local\Programs\PPTADDINMANAGER\`  
   and create a shortcut pointing to this managed version.

---

## ⚙️ Requirements

- Windows 10 or later
- Microsoft PowerPoint (Office 2016 or newer recommended)
- Internet connection (to access GitHub)

---

## 🛡️ Security

All downloaded add-ins are:
- Digitally signed (`.sig` files)
- Verified locally before installation or update

---

## 📚 Roadmap

- [x] PowerPoint add-in management
- [ ] Support for Word / Excel / Outlook
- [ ] Standalone executable management
- [ ] Advanced configuration UI
- [ ] Proxy auto-detection
- [ ] Optional automatic repo discovery

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to submit issues or pull requests via [GitHub Issues](https://github.com/Tangui-Gouirand/PPT-ADDIN-MANAGER/issues).

---

## 👤 Author

Developed by **Tangui Gouirand**  
💡 Simple tools for demanding users.
