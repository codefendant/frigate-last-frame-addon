# Home Assistant Add-on: Frigate Last Frame Test

Experimental Raspberry Pi ARM64 Frigate build used to test optional display of the most recent frame while a camera is intentionally disabled.

The add-on uses `ghcr.io/codefendant/frigate:last-frame-rpi` and is intended to run separately from the official Frigate add-on. Do not run both Frigate add-ons at the same time.

Create a `config.yml` file in this add-on's configuration folder before starting it.

The feature remains disabled by default. Enable it per camera with:

```yaml
live:
  show_last_frame_when_off: true
```

Only `aarch64` is supported by this test package.
