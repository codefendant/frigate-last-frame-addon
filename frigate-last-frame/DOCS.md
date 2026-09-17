# Frigate Last Frame Test

This is an experimental Home Assistant add-on for testing the `show_last_frame_when_off` Frigate feature.

Create a `config.yml` file in this add-on's configuration folder before starting it. The test add-on has a separate configuration directory from the official Frigate add-on.

Do not run this test add-on and the official Frigate add-on at the same time.

For the first test, enable the feature only for `magicam01`:

```yaml
cameras:
  magicam01:
    live:
      show_last_frame_when_off: true
```

Keep the rest of the existing `magicam01` camera configuration unchanged.
