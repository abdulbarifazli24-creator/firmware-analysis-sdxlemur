# SDXLEMUR Firmware Analysis

This repository contains tools and workflows for analyzing and rebuilding firmware for Qualcomm SDXLEMUR-based routers and modems. It supports extracting YAFFS file systems, identifying kernel modules, and compiling custom OpenWrt firmware optimized for gaming and advanced networking.

## Features

- 📦 Extract and inspect firmware images
- ⚙️ Build OpenWrt firmware using GitHub Actions
- 🎮 Optimize for PUBG, VPN, DNS, NAT, and QoS
- 📱 Fully mobile-compatible workflow (Termux + cloud)

## Device Info

- Model: SDXLEMUR MTP MBB PCIE V4
- Kernel: 5.4.210-perf
- Firmware: v1.31
- CPU: ARMv7
- Modem: RG520N-EB

## How to Use

1. Clone this repo
2. Upload your `.config` file
3. Run the GitHub Action: **Build OpenWrt Firmware**
4. Download the compiled image from the Artifacts section

## License

This project is open-source under the MIT License.

## Contributions

Pull requests and feedback are welcome. Let's build better firmware together!

## LCD Display Control

This device includes a built-in LCD screen for displaying time, battery status, and system info. Future updates will include GPIO-based control to toggle the display on/off via software switch.

### Planned Features

- 🖥️ Display system status (IP, uptime, signal strength)
- 🔘 Toggle LCD on/off via OpenWrt LuCI or SSH
- ⚡ Auto-dim or sleep mode when idle
- 🔌 GPIO mapping for power control

### Device Reference

- Brand: CHANEVE
- Chipset: Qualcomm SDX62 Snapdragon
- Display: Internal LCD (shown in attached images)
