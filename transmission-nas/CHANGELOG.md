## Fix

- **Set `init: false` in `config.json`.** The base image bump in v2.0.0 brought s6-overlay v3, which strictly requires `/init` to be PID 1. By default HA Supervisor wraps the container with Docker's tini as PID 1, leaving `/init` as PID 2 — s6-overlay-suexec then bails with `fatal: can only run as pid 1` and the addon won't start. Disabling Supervisor's tini wrapper makes `/init` PID 1 directly, matching upstream `hassio-addons/*` conventions for the same base.

If you saw v2.0.0 fail to start with `s6-overlay-suexec: fatal: can only run as pid 1`, this release fixes it.