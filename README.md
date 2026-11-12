# ⚡ BloxClaimer (Pro Automation)

> **BloxClaimer** is an advanced, automated Roblox promo code redemption desktop application designed to streamline claiming game rewards effortlessly. 

---

## 🤖 Developed with Artificial Intelligence

This project was built almost entirely with the assistance of **Artificial Intelligence**. From architecting the background Flask server and designing the sleek, modern `CustomTkinter` user interface to engineering the automation macros and handling complex edge cases, AI played a central role throughout the entire development lifecycle. 

Because this tool was shaped by AI-driven programming, you might occasionally encounter unexpected bugs or quirks. If you run into any issues or have suggestions, please feel free to report them so we can improve the application together!

---

## ✨ Key Features

* **🎨 Modern Cyberpunk UI:** Built with `CustomTkinter` and Windows Mica styling support, offering smooth Light/Dark mode switching and custom accent color pickers.
* **🌐 Automated Web Bridge (Tampermonkey):** Seamlessly communicates via a background Flask server (`localhost:5000`) to grab game data, avatars, and high-res thumbnails instantly when you click "Play" on Roblox.
* **📂 Dynamic Database Import:** Easily update your game codes library on the fly without recompiling the app by importing external master database files (`.json`) directly through the **Settings** page.
* **⚡ Smart Auto-Scale Typography:** Automatically adjusts font sizes for long game titles to ensure a clean, flawless interface layout.
* **🤖 Intelligent Macro Automation:** Safely copies, pastes, and redeems codes with customizable delays, auto-Enter triggers, and a built-in safety abort switch.
* **🔄 Live State Tracking:** Automatically monitors your active game sessions via `psutil` and resets the interface back to standby the moment Roblox closes.

---

## 🛠️ Tech Stack & Libraries

* **Python 3.x**
* **CustomTkinter** (Modern UI Framework)
* **Flask** (Local background bridge server)
* **PyAutoGUI & Pyperclip** (Cross-platform macro automation)
* **BeautifulSoup4 & Requests** (Web scraping fallback engine)
* **Psutil** (System process monitoring)
* **PyWinStyles** (Windows native window styling effects)

---

## 🚀 Installation & Setup

1. **Clone or Download the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/BloxClaimer.git](https://github.com/YOUR_USERNAME/BloxClaimer.git)
   cd BloxClaimer
