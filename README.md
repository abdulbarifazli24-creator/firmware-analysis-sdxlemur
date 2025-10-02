# SDXLEMUR Firmware Analysis

This repository contains tools and workflows for analyzing and rebuilding firmware for Qualcomm SDXLEMUR-based routers and modems. It supports extracting YAFFS file systems, identifying kernel modules, and compiling custom OpenWrt firmware optimized for gaming and advanced networking.

## Features

- 📦 Extract and inspect firmware images
- ⚙️ Build OpenWrt firmware using GitHub Actions
- 🎮 Optimize for PUBG, VPN, DNS, NAT, and QoS
- 📱 Fully mobile-compatible workflow (Termux + cloud)

## Device Info

- Model: SDXLEMUR MTP MBB PCIE V2
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
