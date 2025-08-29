# Meshtastic CJK Releases

Meshtastic firmware with Chinese, Japanese & Korean support - because why not have mesh networks that speak your language? 🌏

## What's this about?

Just some unofficial firmware builds that let your Meshtastic devices display CJK characters properly. No more weird squares or broken text when your friends send messages in Chinese, Japanese, or Korean.

Made by TSAO (hey꩜tsao.dev) | Based on [Meshtastic](https://github.com/meshtastic) | GPLv3 license

## The Fine Print 📝

- **Testing only**: This stuff is for testing/fun, not production. If it breaks something, that's on you
- **Unofficial**: This isn't from the official Meshtastic team - just a side project
- **No warranty**: It works on my machine ¯\_(ツ)_/¯
- **Don't sell these**: Please don't make money off these builds (though legally you could under GPLv3)
- **CJK code**: The CJK display stuff is my work. [Patch files here](https://github.com/whywilson/meshtastic-firmware/commit/fd672aa0e4172a28f2c4f06c9b8d1b4ab86aacb6#diff-efc04cdb1a550eb433fb6d101f1de4c358546a8b02a7e0b5b17256f60d6e0869) if you want to see how it works

## How to Flash This Thing 🔧

Pick your poison:

- **Easy mode**: Go to [flasher.meshtastic.org](https://flasher.meshtastic.org) and flash it from your browser
- **DIY mode**: Download from [releases](https://github.com/csrutil/meshtastic-releases) and flash manually

## What Devices Work? 📱

Works with ESP32 and nRF52 boards. Here's what I've tested:

### Some Pretty Pictures 📸

<img src="assets/gat562_mesh_trial_tracker.jpeg" alt="GAT562 Mesh Trial Tracker" width="400">
<img src="assets/heltec-v3.jpeg" alt="Heltec V3" width="400">

### The Full Device List

| **Device Name**                   | **Brand**    | **Category**   | **Key Features**                         |
| --------------------------------- | ------------ | -------------- | ---------------------------------------- |
| **GAT562 EVB Pro**                | GAT-IoT      | Tracker Board  | Pro evaluation board variant             |
| **GAT562 Solar Relay**            | GAT-IoT      | Relay Node     | Solar-powered relay device               |
| **GAT562 Tracker (Trial)**        | GAT-IoT      | Tracker        | Out-of-box trial version                 |
| **Heltec Mesh Node T114**         | Heltec       | Mesh Node      | T114 variant for mesh communication      |
| **Heltec Pocket 5000 (Ink HUD)**  | Heltec       | Pocket Device  | 5,000mAh battery, e-ink display          |
| **Heltec Pocket 10000 (Ink HUD)** | Heltec       | Pocket Device  | 10,000mAh battery, e-ink display         |
| **Heltec V3**                     | Heltec       | General Device | 3rd generation multipurpose device       |
| **Heltec Wireless Tracker**       | Heltec       | Tracker        | Wireless tracking device                 |
| **WIO Tracker L1**                | Seeed Studio | Tracker        | Compact GPS-enabled tracking board       |
| **nRF52 Pro Micro (TCXO)**        | DIY / Nordic | DIY Board      | With temp-compensated crystal oscillator |
| **nRF52 Pro Micro (XTAL)**        | DIY / Nordic | DIY Board      | With standard crystal oscillator         |
