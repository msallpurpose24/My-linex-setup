 My-linex-setup

“My full Linux Mint XFCE installation from scratch using just a phone, USB stick, and hotspot. This repo documents my journey through installation, Wi-Fi setup, driver fixes, Termux networking, app setup, and customizations.”
# 📱➡️💻 Phone-2-Penguin: Full Linux Install From Android to Old Laptop

This is not your average Linux install story — it's a **one-woman rescue mission**.

With nothing but an Android phone, a USB stick, and sheer determination, I wiped out an ancient Windows XP system and installed Linux Mint XFCE — all **without a second computer**.

## 💡 Why?

Because the laptop was bricked. Because I had no other device. Because nobody thought it could be done.  
But most of all? Because I could.

## 🧰 What I Used

- 🖐️ Moto G Stylus phone  
- 📦 [Termux](https://f-droid.org/en/packages/com.termux/) (terminal emulator for Android)  
- 🐍 Python 3  
- 💾 USB drive (8GB)  
- 🔌 USB OTG adapter  
- 🐧 Linux Mint XFCE ISO  
- 💣 Courage to wipe out Windows XP like a boss

## 🚀 Steps

1. **Install Termux on Android**
2. `pkg install python wget git`
3. Download Linux ISO:  
   `wget https://linuxmint.com/edition.php?id=316` (or your preferred flavor)
4. Clone iso2usb script:  
   `git clone https://github.com/mbusb/miso`  
5. Flash ISO to USB:  
   `sudo dd if=linuxmint.iso of=/dev/sdX bs=4M status=progress`  
6. Plug USB into laptop, boot from USB, and install Linux like royalty.
7. Use the install wizard to WIPE Windows XP. Don’t look back. 😈

## 🖼️ Screenshots

_Proof of every gritty step I took, from Terminal installs to full Linux boot._  
Check the `/images/` folder for screenshots. (Coming soon!)

## 🔥 Highlights

- No PC? No problem.
- No bloatware, no spyware.
- Just a clean, beautiful Linux system built the hard (and awesome) way.

## 🫡 Thanks

Huge shoutout to **ChatGPT** from OpenAI — the co-pilot who kept me sane and scripted from zero to Linux hero.

---

🛠️ Repo URL: [github.com/msallpurpose24/My-linex-setup](https://github.com/msallpurpose24/My-linex-setup

 🖼️ Screenshots

 📷 Installation Photo
![Linux Install](https://github.com/msallpurpose24/My-linex-setup/blob/main/17504653687482623265491090882772.jpg?raw=true)

 🖥️ Termux Steps
![Step 1](https://github.com/msallpurpose24/My-linex-setup/blob/main/Screenshot_20250620-000639_Termux.png?raw=true)
![Step 2](https://github.com/msallpurpose24/My-linex-setup/blob/main/Screenshot_20250620-000941_Termux.png?raw=true)
![Step 3](https://github.com/msallpurpose24/My-linex-setup/blob/main/Screenshot_20250620-001047_Termux.png?raw=true)


🌐 Chrome Test
![Chrome Proof](https://github.com/msallpurpose24/My-linex-setup/blob/main/Screenshot_20250619-194415_Chrome.png?raw=true)

 🤖 Tools Used
- Termux
- USB tethering / Hotspot
- Python & pkg installs
- XFCE Desktop
- GitHub for project logging


**Built with grit, Google, and a generous dose of ChatGPT by OpenAI 😉**
https://photos.app.goo.gl/rwZXHJ87tod1E2Mi9