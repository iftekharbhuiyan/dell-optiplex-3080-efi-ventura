# Dell Optiplex 3080 MFF EFI - macOS Ventura

[![Static Badge](https://img.shields.io/badge/macOS-Ventura-orange)](https://developer.apple.com/documentation/macos-release-notes/macos-13-release-notes)
[![Static Badge](https://img.shields.io/badge/OpenCore-1.0.6-blue)](https://github.com/acidanthera/OpenCorePkg/releases/tag/1.0.6)
[![Static Badge](https://img.shields.io/badge/License-MIT-purple)](/LICENSE)

<p>Dell Optiplex 3080 Micro Form Factor OpenCore EFI build for macOS Ventura v13.7.8.</p>

## Screenshot

<p>
<figure>
<img src="./screenshots/desktop.png" alt="macOS Ventura Desktop" />
<figcaption>Screenshot of the macOS Ventura Desktop.</figcaption>
</figure>
</p>

## Specification

| Device       | Model                               | Status |
| ------------ | ----------------------------------- | ------ |
| CPU          | Intel Core i5-10500T                | Works  |
| GPU          | Intel UHD Graphics 630              | Works  |
| Memory       | Crucial 16GB DDR4 2666 MHz          | Works  |
| Drive        | Samsung PM991a NVMe 512GB           | Works  |
| Audio        | Realtek ALC3246                     | Works  |
| WiFi & BT    | Intel Wireless-AC 8265NGW           | Works  |
| Ethernet     | Realtek RTL8111 GbE Controller      | Works  |
| Speaker      | Internal                            | Works  |

## BIOS Setup

<p>The BIOS had been upgraded to v2.33.0 and following settings has been changed in order to make the installation process smoother.</p>

<details>
<summary><strong>BIOS Options</strong></summary><br/>
<ul>
<li>Integrated NIC - Enabled</li>
<li>SATA Operation - AHCI</li>
<li>Primary Display - Intel HD Graphics</li>
<li>TPM 2.0 Security - Unchecked</li>
<li>SMM Security Mitigation - Unchecked</li>
<li>Secure Boot Enable - Unchecked</li>
<li>Secure Boot Mode - Audit Mode</li>
<li>Intel SGX Enable - Disabled</li>
<li>C-States Control - Checked</li>
<li>Deep Sleep Control - Disabled</li>
<li>Wakes on LAN/WLAN - LAN Only</li>
<li>Block Sleep - Checked</li>
<li>Fastboot - Minimal</li>
<li>ASPM - Disabled</li>
<li>Virtualization - Enable Intel Virtualization Technology</li>
<li>VT for Direct I/O - Enable VT for Direct I/O</li>
<li>UEFI Boot Path Security - Always, Except Internal HDD</li>
</ul>
</details>

## Notes

<p>Pretty much everything worked as expected.</p>

## Credits

- [Acidanthera](https://github.com/acidanthera) - OpenCorePkg
- [lzhoang2801](https://github.com/lzhoang2801) - OpenCore Simplify
- [OpenIntelWireless](https://github.com/OpenIntelWireless) - Intel Wireless
- [Mieze](https://github.com/Mieze) - Realtek RTL8111
- [ic005k](https://github.com/ic005k) - OC Auxiliary Tools
- [corpnewt](https://github.com/corpnewt/) - ProperTree
- [badges](https://github.com/badges) - Shields.io
