# Arabic Custom 102 Keyboard Layout

<p align="center">
  <img src="https://raw.githubusercontent.com/abaalmufry/arabic-custom-102-xkb/main/images/rIGkL.jpg" width="850" alt="Arabic 102 Keyboard Layout">
</p>

**Languages:** 🇺🇸 English | [🇸🇦 العربية](README-ar.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

Windows Arabic (102) keyboard layout for Linux Mint and Debian-based Linux distributions.

This project provides an XKB layout that closely matches the behavior of the Microsoft Windows Arabic (102) keyboard layout while integrating cleanly with the Linux XKB infrastructure.

Arabic speakers who are accustomed to the Windows Arabic (102) layout can switch to Linux without having to relearn key positions.

---

## Why this project?

Many Linux distributions do not provide a keyboard layout that fully matches the Microsoft Windows Arabic (102) layout.

For users who have spent years typing on Windows, switching to Linux often means relearning key positions and keyboard shortcuts.

This project aims to provide a familiar typing experience by reproducing the Windows Arabic (102) layout as closely as possible while remaining fully compatible with the standard XKB infrastructure.

---

## Features

- Nearly identical to Microsoft Windows Arabic (102)
- Dedicated **ذ** key next to the Enter key
- Supports both:
  - Left Alt + Shift
  - Right Alt + Shift
- AltGr combinations preserved
- Native XKB implementation
- System-wide installation
- Debian package (.deb)
- Clean installation, upgrade and removal
- Open Source

---

## Compatibility

Tested on:

- Linux Mint 22.3 XFCE

Compatible with most Debian-based distributions that use XKB.

---

## Installation

Download the latest Debian package from the Releases page.

Install using your package manager or:

```bash
sudo dpkg -i arabic-custom-102-xkb_1.0.0 .deb
```

Log out and log back in.

Open:

Settings → Keyboard → Layouts

Select:

```
Arabic (102) - Windows Layout
```

---

## Removal

```bash
sudo apt purge arabic-custom-102-xkb
```

---

## Upgrade

Install a newer package over the existing one:

```bash
sudo dpkg -i arabic-custom-102-xkb_<version> .deb
```

No manual removal is required.

---

## Project Goals

- Reproduce the Windows Arabic (102) typing experience
- Keep full compatibility with Linux XKB
- Avoid custom patches to desktop environments
- Provide a clean Debian package
- Make installation simple for end users

---

## Status

Current release:

**v1.0.0**

This is considered the first stable release.

---

## Contributing

Contributions are welcome.

You can help by:

- Reporting bugs
- Improving documentation
- Testing on additional Linux distributions
- Reviewing keyboard mappings
- Submitting pull requests

Please keep the keyboard layout compatible with the Windows Arabic (102) layout unless there is a strong technical reason.

---

## License

This project is released under the : MIT License.

See the LICENSE file for details.

---

## Acknowledgments

Thanks to everyone who tested and reviewed the keyboard layout.
