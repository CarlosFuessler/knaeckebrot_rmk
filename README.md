# ⌨️ Kneackebrot 🚀

> **A crispy, wireless split keyboard experience powered by RMK.**

The **Kneackebrot** is a high-performance, split mechanical keyboard built for speed, comfort, and ultimate wireless freedom. Running on the cutting-edge **RMK** (Rust Management for Keyboards) engine, it combines the stability of Rust with the flexibility of real-time remapping.

---

## ✨ Features

* **󰌌 Vial-Native:** No more recompiling. Remap keys, macros, and layers in real-time using the [Vial Web App](https://get.vial.today/).
* **󰀂 Wireless Split:** Powered by nRF52840, providing a clean, cable-free desk setup via Bluetooth Low Energy (BLE).
* **󱊄 USB-Priority Intelligence:** Automatically switches to USB mode when plugged in, or use **User11** to stay on BLE while charging.
* **🦀 Powered by RMK:** Built with the safety and speed of the Rust programming language.

---

## 📥 Getting Started (No Coding Required!)

Forget about installing compilers or setting up Rust environments. Everything is ready for immediate action.

### 1. Download the Goods
Head over to the **[󰒲 Releases](../../releases)** tab and grab the latest `.uf2` firmware file for your Kneackebrot.

### 2. Enter Warp Speed (Bootloader Mode)
Connect your board via USB and **double-tap the Reset button** quickly. A new drive named `NICENANO` will appear on your computer.

### 3. Flash & Go 󱊏
Simply **drag and drop** the `.uf2` file onto the `NICENANO` drive. The board will flash, restart, and your new layout is live!

---

## 🛠️ Customize on the Fly

The Kneackebrot is **Vial-ready**. 
1. Open [Vial](https://get.vial.today/) in your browser or download the desktop app.
2. Connect your keyboard.
3. Start tweaking your layout, layers, and encoder settings instantly.

---

##  Important Notes for nRF52840

* **󰂯 Bluetooth Stack:** RMK (v0.7+) uses its own Bluetooth stack. If you ever want to switch to ZMK, you will need to [re-flash your bootloader](https://nicekeyboards.com/docs/nice-nano/troubleshooting#my-nicenano-seems-to-be-acting-up-and-i-want-to-re-flash-the-bootloader).
* **󰚥 Connection Priority:** If a cable is plugged in, it defaults to USB. To switch to wireless while the cable is in, use your assigned **Switch Output** key.

---

## ❤️ Credits

Huge shoutout to the **[RMK Project](https://github.com/HaoboGu/rmk)**. This keyboard wouldn't be nearly as "crispy" without their incredible work on providing a feature-rich and easy-to-use Rust firmware.

---
*Stay crispy. Keep typing.*if a USB cable is connected. After flashing, remember to disconnect the USB cable, or [switch to BLE-priority mode](https://rmk.rs/docs/features/wireless.html#multiple-profile-support) by pressing User11(Switch Output) key.
