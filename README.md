# Frigate Last Frame Test Home Assistant Add-on

Home Assistant add-on repository for testing the Frigate `show_last_frame_when_off` feature on Raspberry Pi ARM64.

## Install repository

Add this repository to the Home Assistant App Store repositories:

`https://github.com/codefendant/frigate-last-frame-addon`

Then install **Frigate Last Frame Test**.

The test add-on uses the public image `ghcr.io/codefendant/frigate:last-frame-rpi`. It has its own add-on configuration directory and should not be run at the same time as the official Frigate add-on.
