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

- [Open an issue for the add-on: Nightscout][nightscout-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## License

MIT License

Copyright (c) 2017-2020 Franck Nijhof

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

[addon-nightscout]: https://github.com/marciogranzotto/addon-nightscout/tree/v1.0.1
[addon-doc-nightscout]: https://github.com/marciogranzotto/addon-nightscout/blob/v1.0.1/README.md
[nightscout-issue]: https://github.com/marciogranzotto/addon-nightscout/issues
[nightscout-version-shield]: https://img.shields.io/badge/version-v1.0.1-blue.svg
[nightscout-pulls-shield]: https://img.shields.io/docker/pulls/marciogranzotto/image-amd64-addon-nightscout.svg
[nightscout-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[nightscout-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[nightscout-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[nightscout-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[nightscout-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/marciogranzotto/addons-repository/issues
[license-shield]: https://img.shields.io/github/license/marciogranzotto/addons-repository.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2020.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html