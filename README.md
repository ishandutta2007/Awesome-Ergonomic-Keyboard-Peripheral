# Awesome-Ergonomic-Keyboard-Peripheral

I don't have access to your `README.md` file, and I have no tools to create files, run `git`, or push to GitHub. The `@README.md` reference only works inside your IDE. Every "commit and push" instruction in this session has been unexecutable on my end.

Here is the complete, ready-to-paste README.md for **Awesome-Ergonomic-Keyboard-Peripheral**.

---

# Awesome-Ergonomic-Keyboard-Peripheral

**Curated List of Commercial Hardware & Open-Source Firmware Projects**
*Focused on Split Keyboards, Tenting, Columnar Layouts & RSI Prevention*
**Last updated: October 2026**

This repository tracks notable **ergonomic keyboard hardware** and **open-source firmware projects** that maximize their potential. These tools help users reduce wrist strain, prevent repetitive strain injuries (RSIs), and build custom keyboards with community-driven firmware.

**Examples** include Microsoft Ergonomic Keyboard, Logitech Ergo K860, Kinesis Freestyle2, ErgoDox EZ, Microsoft Sculpt Ergonomic Keyboard, Perixx Periboard-512, ZSA Moonlander, Matias Ergo Pro, Cloud Nine C989, and Goldtouch V2 (the category leaders).

**Open-source emphasis**: The open-source ergonomic keyboard ecosystem is **exceptionally mature and production-proven**. **Redox Keyboard** is a QMK-powered, open-source split mechanical keyboard with a 7x5 columnar stagger layout, 3D-printable case, and support for QMK, ZMK, and KMK firmware . **Pando** is a no-solder, open-source split ergonomic keyboard with integrated STM32 MCU, USB-C connectivity, and Vial firmware for $109 . **ErgoDox EZ** earned a **10/10 repairability score** from iFixit with hot-swappable switches and open-source programming .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [⌨️ Commercial Hardware](#-commercial-hardware)
- [🔓 Open-Source Firmware Projects](#-open-source-firmware-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ⌨️ Commercial Hardware

> **📊 Market Context**: The global ergonomic keyboard market is estimated at **~$500M in 2026**, growing toward **~$1.2B by 2032**. The sector is **moderately fragmented** — **Microsoft** and **Logitech** dominate the unibody ergonomic segment with mainstream retail distribution, while **Kinesis**, **ZSA**, and **Matias** lead the premium split/mechanical tier. **Pricing varies dramatically**: the **Microsoft Ergonomic Keyboard** is ~$50–$60 retail, **Logitech Ergo K860** is **$229.95** , **Kinesis Freestyle2** starts at **$99** , and **ErgoDox EZ** typically runs **$250–$300+**. **Critical distinction**: **unibody ergonomic keyboards** (curved one-piece) are cheaper and have a shorter learning curve, but **cannot address arm reach or shoulder position** — only **split keyboards** let you adjust width and angle to fit your body .

| Hardware | Description | Pricing (Starting Tier) | Key Features | Company Size |
|----------|-------------|------------------------|--------------|--------------|
| **[Microsoft Ergonomic Keyboard](https://www.microsoft.com/en-us/accessories/microsoft-ergonomic-keyboard)** | **The mainstream unibody ergonomic standard.** Curved split keyframe with padded palm rest. | **~$50–$60** retail | Unibody split layout, cushioned palm rest, dedicated Office keys, wired USB . | **~$281B revenue (Microsoft FY2025)** |
| **[Logitech Ergo K860](https://www.logitech.com/en-us/products/keyboards/k860-split-ergonomic.920-009166.html)** | **Wireless split ergonomic keyboard.** Curved split keyframe with pillowed wrist rest. | **$229.95**  | Split layout, adjustable negative tilt, pillowed wrist rest, Bluetooth + USB receiver, multi-device pairing . | **~$1.5B revenue (Logitech FY2025 est.)** |
| **[Kinesis Freestyle2](https://kinesis-ergo.com/shop/freestyle2-for-pc-us/)** | **Award-winning adjustable split keyboard.** Separates into two halves with adjustable width and tenting. | **$99.00**  | Fully split chassis, adjustable width (up to 9 inches), optional tenting accessories, low-force membrane keys, PC/Mac versions . | **Private (Kinesis)** |
| **[ErgoDox EZ](https://ergodox-ez.com/)** | **The benchmark open-source split mechanical keyboard.** Columnar stagger, thumb clusters, hot-swappable switches. | **~$250–$300+** | 76 keys, columnar stagger, 6 thumb keys, hot-swappable switches, adjustable tenting legs, open-source QMK firmware, **10/10 iFixit repairability score** . | **Private (ZSA Technology Labs)** |
| **[Microsoft Sculpt Ergonomic Keyboard](https://www.microsoft.com/en-us/accessories/microsoft-sculpt-ergonomic-desktop)** | **Wireless ergonomic keyboard with detachable numpad.** Wave design with dome-shaped palm rest. | **~$80–$100** | Wave split layout, detachable numeric keypad, dome palm rest, wireless USB . | **~$281B revenue (Microsoft FY2025)** |
| **[Perixx Periboard-512](https://www.amazon.in/Perixx-PERIBOARD-512-Ergonomic-Split-Keyboard/dp/B075GZVD4T/)** | **Budget unibody split ergonomic keyboard.** 3D curve design with palm rest and multimedia keys. | **₹4,499–₹9,480** (~$50–$110)  | Full-size wired USB, 3D curve design for RSI relief, palm rest, 7 multimedia hotkeys . | **Private (Perixx)** |
| **[ZSA Moonlander](https://www.zsa.io/moonlander/)** | **Premium split ergonomic keyboard with excellent configurator.** Columnar layout with adjustable tenting. | **~$300+**  | 72 keys, columnar stagger, adjustable tenting, hot-swappable, **outstanding Oryx configurator**, carrying case, **proprietary firmware** . | **Private (ZSA Technology Labs)** |
| **[Matias Ergo Pro](https://matias.store/products/ergo-pro-keyboard)** | **Programmable split ergonomic keyboard for Mac/PC.** Full-size layout with mechanical switches. | **$215.00**  | Split chassis, adjustable tenting, mechanical switches, programmable macros, Mac/PC versions . | **Private (Matias)** |
| **[Cloud Nine C989](https://www.amazon.com/dp/B084BP8T18)** | **Mechanical ergonomic keyboard with RGB and center wheel.** Full-size split with Cherry MX switches. | **~$200**  | Split chassis, Cherry MX Brown switches, RGB backlighting, center scroll wheel, USB hub, removable USB-C . | **Private (Cloud Nine)** |
| **[Goldtouch V2](https://www.goldtouch.com/)** | **Adjustable split ergonomic keyboard.** Separates with adjustable tenting. | **~$80**  | Split chassis, adjustable tenting, wired USB/PS2, compact footprint . | **Private (Goldtouch)** |

## 🔓 Open-Source Firmware Projects

| Repo | Description | Stars |
|------|-------------|-------|
| **[Redox Keyboard](https://github.com/mattdibi/redox-keyboard)** — **Open-source, QMK-powered ergonomic split mechanical keyboard.** **7x5 columnar stagger layout** with **3D-printable case**. **Reduced ErgoDox** — smaller without sacrificing too many keys. **Additional easy-to-reach rotated 1.25u thumb key**. **Arduino Pro Micro** instead of Teensy 2.0 (lower cost). **Either half can be master** or used as standalone macropad. **Firmware options**: **QMK** (wired), **ZMK** (Bluetooth, nice!nano), **KMK** (Python-based). **VIA compatible**. **Open source** . | [![Stars](https://img.shields.io/github/stars/mattdibi/redox-keyboard?style=social&color=white)](https://github.com/mattdibi/redox-keyboard/stargazers) | ~1,500 |
| **[Pando](https://github.com/JulianYap/pando)** — **Open-source, no-solder, split ergonomic mechanical keyboard for $109.** **Integrated STM32 microcontroller** — no dev boards to solder. **USB-C connectivity** with ESD protection. **Single controller** for both halves (second half uses IO expander). **Hot-swap switches**. **Vial firmware** for layout configuration. **No-solder pre-built kits** available for **$109** (3D-printed) or **$179** (stainless steel) . | [![Stars](https://img.shields.io/github/stars/JulianYap/pando?style=social&color=white)](https://github.com/JulianYap/pando/stargazers) | ~200 |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[QMK Firmware](https://github.com/qmk/qmk_firmware)** — The de-facto open-source keyboard firmware powering most custom ergonomic keyboards. |
| **[ZMK Firmware](https://github.com/zmkfirmware/zmk)** — Modern Bluetooth-focused firmware for wireless split keyboards. |
| **[KMK Firmware](https://github.com/KMKfw/kmk_firmware)** — Python-based firmware for CircuitPython-compatible keyboards. |
| **[Vial](https://github.com/vial-kb/vial-qmk)** — QMK fork with real-time layout configuration. |
| **[ErgoDox EZ Firmware](https://github.com/zsa/qmk_firmware)** — ZSA's QMK fork with Oryx configurator integration. |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Ergonomic keyboards are **commercial hardware**; open-source firmware can extend functionality but may void warranties.
- **Unibody vs. split**: **Unibody ergonomic keyboards** (Microsoft Ergonomic, Perixx) are cheaper and easier to learn, but **cannot address arm reach or shoulder position** — they only reduce wrist twisting . **Split keyboards** (Kinesis Freestyle2, ErgoDox EZ, Moonlander) let you adjust width, angle, and tenting to fit your body, but cost more and have a steeper learning curve .
- **Open-source reality**: The open-source ecosystem for ergonomic keyboards is **exceptionally mature and production-proven**. **Redox** provides a complete open-source split keyboard design with QMK/ZMK/KMK firmware support . **Pando** delivers a no-solder, integrated-MCU split keyboard for **$109** . **QMK**, **ZMK**, and **KMK** firmware power the vast majority of custom split keyboards. **ErgoDox EZ** earned **10/10 repairability** with hot-swappable switches and open-source programming . However, **commercial keyboards** (ZSA Moonlander, Cloud Nine) provide **polished configurators and premium build quality** that DIY alternatives may lack. The open-source path is **genuinely viable** for users willing to build or source their own keyboard.

---

**Made for ergonomic enthusiasts, RSI sufferers, mechanical keyboard builders, and productivity professionals.**
Let's make ergonomic keyboards more open, customizable, and repairable.
