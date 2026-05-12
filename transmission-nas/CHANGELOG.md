## Highlights

- **Transmission 3.00 → 4.0.6.** Major upstream version bump; ships the rewritten Transmission 4 web UI.
- **Base image: `hassio-addons/base` 9.1.5 → 18.2.1** (Alpine 3.12 → 3.22). Last base release that still ships all five architectures — aarch64, amd64, armhf, armv7, i386 all remain supported.
- Refreshed Alpine package pins: `coreutils 9.7-r1`, `openvpn 2.6.20-r0`, `nginx 1.28.3-r0`, `cifs-utils 7.3-r0`.

## Notes for users

- The web UI looks different — Transmission 4 ships a redesigned single-page UI bundled into `transmission-app.js`. Same workflows, new look.
- Existing `/data/transmission/settings.json` is preserved across the upgrade; TM 4 reads the same config keys this addon writes.
- User-facing config schema (network share mount, OpenVPN, auth) is unchanged.

## Maintenance

- Ingress patch retargeted at TM 4's new web layout (`/usr/share/transmission/public_html/transmission-app.js`), with a build-time `grep` guard that fails the image build loudly if a future upstream bundler change ever stops matching — preventing silent ingress regressions.