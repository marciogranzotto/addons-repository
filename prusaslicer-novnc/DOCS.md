# Home Assistant Add-On for Nightscout

This is a Home Assistant Add-on that runs PrusaSlicer on a Debian container and exposes the GUI via NoVNC as a webpage.
Based on [helfrichmichael/prusaslicer-novnc](https://github.com/helfrichmichael/prusaslicer-novnc) and [Poeschl's vnc-viewer add-on](https://github.com/Poeschl/Hassio-Addons/tree/master/vnc-viewer)

## Installation

The installation of this add-on is pretty straightforward and not different in
comparison to installing any other Home Assistant add-on.

1.  [Add our Home Assistant add-ons repository][repository] to your Home Assistant instance.
2.  Install the "PrusaSlicer NoVNC" add-on.
3.  Check the "Show in sidebar toggle.
4.  Start the "PrusaSlicer NoVNC" add-on
5.  Check the logs of the "PrusaSlicer NoVNC" add-on to see if everything went well.
6.  Open the "PrusaSlicer" tab on Home Assistant.

[:books: Read the full add-on documentation][docs]

**NOTE**: Starting the add-on might take a couple of minutes (especially the
first time starting the add-on).

**NOTE**: Do not add this repository to Home Assistant, please use:
`https://github.com/marciogranzotto/addons-repository`.

## Configuration

When you first run the add-on you will be prompt to configure PrusaSlicer.

It's configuration files are stored under `/config/prusaslicer/.config/PrusaSlicer/`. You can change any files there if wanted. They will be persistent even if you uninstall and reinstall the add-on.

It automatically creates `/share/prusaslicer/3dmodels` and `/share/prusaslicer/prints` folders. You can use them to upload 3D models and export gcode files.

This add-on can also access the `/config`, `/share`, and `/media` folders.

## Changelog & Releases

This repository keeps a change log using [GitHub's releases][releases]
functionality. The format of the log is based on
[Keep a Changelog][keepchangelog].

Releases are based on [Semantic Versioning][semver], and use the format
of `MAJOR.MINOR.PATCH`. In a nutshell, the version will be incremented
based on the following:

-   `MAJOR`: Incompatible or major changes.
-   `MINOR`: Backwards-compatible new features and enhancements.
-   `PATCH`: Backwards-compatible bugfixes and package updates.

[keepchangelog]: http://keepachangelog.com/en/1.0.0/

[releases]: https://github.com/marciogranzotto/addon-prusaslicer-nonvc/releases

[repository]: https://github.com/marciogranzotto/addons-repository
