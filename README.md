# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)](https://github.com/P3TERX/Actions-OpenWrt/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)](https://github.com/P3TERX/Actions-OpenWrt/fork)

Build OpenWrt using GitHub Actions

- Features
  - V1
    - 默认中文
    - kernel 4.19 gcc 8.x glibc
    - focuses on network
    - Lean's OpenWrt
    - Lienol's luci-apps, including Passwall
    - smartdns
    - builds mostly available vpn luci-apps
    - builds mostly available wired network chip kmod drivers, including kmod-usb
    - builds some network diagnosis tools, e.g. knot-dig, nmap, arp-scan, ss
    - open-vm-tools (x86 only)
  - V2
    - 默认中文
    - kernel 5.4 gcc 9.x glibc
    - official OpenWrt master branch
    - minimal build
    - Lean's packages (openwrt-fullconenat luci-app-zerotier luci-app-xlnetacc luci-app-mwan3helper luci-app-syncdial)
    - Lienol's packages (passwall)
    - intel 1000e kmod drivers and vmxnet3 (x86 only), usb: rtl8152, ax88179
    - smartdns
    - open-vm-tools (x86 only)
- Builds
  - x86-64 UEFI
  - AArch64 Raspberry Pi 4B
- Acknowledgments
  - [OpenWrt](https://github.com/openwrt/openwrt)
  - [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
  - [Lienol's OpenWrt Packages](https://github.com/Lienol/openwrt-package)
  - [smartdns](https://github.com/pymumu/smartdns)
  - [open-vm-tools OpenWrt Makefile](https://github.com/srchack/custom-packages)
  - [YYiiEt](https://github.com/YYiiEt/Actions-OpenWrt-RaspberryPi4)
   
[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## Usage

- Click the [Use this template](https://github.com/P3TERX/Actions-OpenWrt/generate) button to create a new repository.
- Generate `.config` files using [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) source code. ( You can change it through environment variables in the workflow file. )
- Push `.config` file to the GitHub repository, and the build starts automatically.Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

## Acknowledgments
- [Microsoft](https://www.microsoft.com)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub](https://github.com)
- [GitHub Actions](https://github.com/features/actions)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cisco](https://www.cisco.com/)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE) © P3TERX
