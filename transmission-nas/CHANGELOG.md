## Fix

- **Set the executable bit on all rootfs init/service scripts.** s6-overlay v3 (which arrived with the v2.0.0 base image bump) strictly requires scripts under `/etc/cont-init.d` and `/etc/services.d/*/run` to have +x; v2 was lenient and ran them anyway. After the bump, all four `cont-init.d` scripts plus both service `run` + `finish` scripts (and the openvpn `up-transmission.sh` helper) were tracked as `100644` and failed at startup with `Permission denied` (exit 126), leaving the addon in `error` state with no transmission daemon running.

If you saw v2.0.0 or v2.0.1 either crash at startup or come up but never actually run transmission, this release fixes it.