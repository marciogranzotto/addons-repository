# Home Assistant Add-ons repository

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, high quality, add-ons that allow you to take your automated
home to the next level.

## Installation

In general, there is no need to install this repository on your
Home Assistant instance. It is activated and added by Home Assistant
by default.

However, if the repository is missing on your setup, adding this add-ons
repository to your Home Assistant instance is pretty easy. In the
Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/marciogranzotto/addons-repository
```

## Add-ons provided by this repository

### &#10003; [Lovelace Kindle Screensaver][addon-lovelace-kindle-screensaver]

![Latest Version][lovelace-kindle-screensaver-version-shield]
![Supports armhf Architecture][lovelace-kindle-screensaver-armhf-shield]
![Supports armv7 Architecture][lovelace-kindle-screensaver-armv7-shield]
![Supports aarch64 Architecture][lovelace-kindle-screensaver-aarch64-shield]
![Supports amd64 Architecture][lovelace-kindle-screensaver-amd64-shield]
![Supports i386 Architecture][lovelace-kindle-screensaver-i386-shield]
![Docker Pulls][lovelace-kindle-screensaver-pulls-shield]

Display a lovelace page as a screensaver on a jailbroken Kindle

[:books: Lovelace Kindle Screensaver add-on documentation][addon-doc-lovelace-kindle-screensaver]

### &#10003; [Nightscout][addon-nightscout]

![Latest Version][nightscout-version-shield]
![Supports armhf Architecture][nightscout-armhf-shield]
![Supports armv7 Architecture][nightscout-armv7-shield]
![Supports aarch64 Architecture][nightscout-aarch64-shield]
![Supports amd64 Architecture][nightscout-amd64-shield]
![Supports i386 Architecture][nightscout-i386-shield]
![Docker Pulls][nightscout-pulls-shield]

Nightscout acts as a web-based CGM (Continuous Glucose Montinor) to allow multiple caregivers to remotely view a patients glucose data in realtime.

[:books: Nightscout add-on documentation][addon-doc-nightscout]

### &#10003; [PrusaSlicer][addon-prusaslicer-novnc]

![Latest Version][prusaslicer-novnc-version-shield]
![Supports armhf Architecture][prusaslicer-novnc-armhf-shield]
![Supports armv7 Architecture][prusaslicer-novnc-armv7-shield]
![Supports aarch64 Architecture][prusaslicer-novnc-aarch64-shield]
![Supports amd64 Architecture][prusaslicer-novnc-amd64-shield]
![Supports i386 Architecture][prusaslicer-novnc-i386-shield]
![Docker Pulls][prusaslicer-novnc-pulls-shield]

PrusaSlicer NoVNC

[:books: PrusaSlicer add-on documentation][addon-doc-prusaslicer-novnc]

### &#10003; [Telegram Bot Amazon][addon-telegram-bot-amazon]

![Latest Version][telegram-bot-amazon-version-shield]
![Supports armhf Architecture][telegram-bot-amazon-armhf-shield]
![Supports armv7 Architecture][telegram-bot-amazon-armv7-shield]
![Supports aarch64 Architecture][telegram-bot-amazon-aarch64-shield]
![Supports amd64 Architecture][telegram-bot-amazon-amd64-shield]
![Supports i386 Architecture][telegram-bot-amazon-i386-shield]
![Docker Pulls][telegram-bot-amazon-pulls-shield]

A Telegram bot that, if made admin of a group, will delete any message containing an Amazon link and re-post it tagged with the specified affiliate tag.² is an open source modular smart mirror platform.

[:books: Telegram Bot Amazon add-on documentation][addon-doc-telegram-bot-amazon]

### &#10003; [Transmission NAS][addon-transmission-nas]

![Latest Version][transmission-nas-version-shield]
![Supports armhf Architecture][transmission-nas-armhf-shield]
![Supports armv7 Architecture][transmission-nas-armv7-shield]
![Supports aarch64 Architecture][transmission-nas-aarch64-shield]
![Supports amd64 Architecture][transmission-nas-amd64-shield]
![Supports i386 Architecture][transmission-nas-i386-shield]
![Docker Pulls][transmission-nas-pulls-shield]

The torrent client for Home Assistant with OpenVPN and Samba Share support

[:books: Transmission NAS add-on documentation][addon-doc-transmission-nas]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You have several options to get them answered:


You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Lovelace Kindle Screensaver][lovelace-kindle-screensaver-issue]
- [Open an issue for the add-on: Nightscout][nightscout-issue]
- [Open an issue for the add-on: PrusaSlicer][prusaslicer-novnc-issue]
- [Open an issue for the add-on: Telegram Bot Amazon][telegram-bot-amazon-issue]
- [Open an issue for the add-on: Transmission NAS][transmission-nas-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## License

MIT License

Copyright (c) 2020 Marcio Granzotto

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-lovelace-kindle-screensaver]: https://github.com/marciogranzotto/hass-lovelace-kindle-screensaver/releases/tag/v0.0.2
[addon-doc-lovelace-kindle-screensaver]: https://github.com/marciogranzotto/hass-lovelace-kindle-screensaver/blob/v0.0.2/README.md
[lovelace-kindle-screensaver-issue]: https://github.com/marciogranzotto/hass-lovelace-kindle-screensaver/issues
[lovelace-kindle-screensaver-version-shield]: https://img.shields.io/badge/version-v0.0.2-blue.svg
[lovelace-kindle-screensaver-pulls-shield]: https://img.shields.io/docker/pulls/marciogranzotto/addon-lovelace-kindle-screensaver-amd64.svg
[lovelace-kindle-screensaver-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[lovelace-kindle-screensaver-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[lovelace-kindle-screensaver-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[lovelace-kindle-screensaver-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[lovelace-kindle-screensaver-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-nightscout]: https://github.com/marciogranzotto/addon-nightscout/releases/tag/v1.4.1
[addon-doc-nightscout]: https://github.com/marciogranzotto/addon-nightscout/blob/v1.4.1/README.md
[nightscout-issue]: https://github.com/marciogranzotto/addon-nightscout/issues
[nightscout-version-shield]: https://img.shields.io/badge/version-v1.4.1-blue.svg
[nightscout-pulls-shield]: https://img.shields.io/docker/pulls/marciogranzotto/image-amd64-addon-nightscout.svg
[nightscout-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[nightscout-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[nightscout-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[nightscout-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[nightscout-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-prusaslicer-novnc]: https://github.com/marciogranzotto/addon-prusaslicer-novnc/releases/tag/v2.5.0-alpha3
[addon-doc-prusaslicer-novnc]: https://github.com/marciogranzotto/addon-prusaslicer-novnc/blob/v2.5.0-alpha3/README.md
[prusaslicer-novnc-issue]: https://github.com/marciogranzotto/addon-prusaslicer-novnc/issues
[prusaslicer-novnc-version-shield]: https://img.shields.io/badge/version-v2.5.0-alpha3-blue.svg
[prusaslicer-novnc-pulls-shield]: https://img.shields.io/docker/pulls/marciogranzotto/image-amd64-addon-prusaslicer-novnc.svg
[prusaslicer-novnc-aarch64-shield]: https://img.shields.io/badge/aarch64-no-red.svg
[prusaslicer-novnc-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[prusaslicer-novnc-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[prusaslicer-novnc-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[prusaslicer-novnc-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-telegram-bot-amazon]: https://github.com/marciogranzotto/addon-telegram-bot-amazon/releases/tag/v1.0.1
[addon-doc-telegram-bot-amazon]: https://github.com/marciogranzotto/addon-telegram-bot-amazon/blob/v1.0.1/README.md
[telegram-bot-amazon-issue]: https://github.com/marciogranzotto/addon-telegram-bot-amazon/issues
[telegram-bot-amazon-version-shield]: https://img.shields.io/badge/version-v1.0.1-blue.svg
[telegram-bot-amazon-pulls-shield]: https://img.shields.io/docker/pulls/marciogranzotto/addon-telegram-bot-amazon-armhf.svg
[telegram-bot-amazon-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[telegram-bot-amazon-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[telegram-bot-amazon-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[telegram-bot-amazon-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[telegram-bot-amazon-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[addon-transmission-nas]: https://github.com/marciogranzotto/addon-transmission-nas/releases/tag/v1.1.3
[addon-doc-transmission-nas]: https://github.com/marciogranzotto/addon-transmission-nas/blob/v1.1.3/README.md
[transmission-nas-issue]: https://github.com/marciogranzotto/addon-transmission-nas/issues
[transmission-nas-version-shield]: https://img.shields.io/badge/version-v1.1.3-blue.svg
[transmission-nas-pulls-shield]: https://img.shields.io/docker/pulls/marciogranzotto/addon-transmission-nas-armhf.svg
[transmission-nas-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[transmission-nas-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[transmission-nas-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[transmission-nas-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[transmission-nas-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/marciogranzotto/addons-repository/issues
[license-shield]: https://img.shields.io/github/license/marciogranzotto/addons-repository.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2020.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html