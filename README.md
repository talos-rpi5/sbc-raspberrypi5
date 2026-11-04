# sbc-raspberrypi5

This repo provides the overlay for Raspberry Pi 5 generic Talos image. Currently it uses a [U-Boot fork](https://github.com/talos-rpi5/u-boot) which is patched to work with Raspberry Pi 5.

For example usage instructions follow the [boot assets guide](https://docs.siderolabs.com/talos/latest/platform-specific-installations/boot-assets#example-raspberry-pi-overlay-with-imager).

## Overlay Options

| Option            | Description                                                         |
| ----------------- | ------------------------------------------------------------------- |
| `configTxt`       | Completely replace the `config.txt` file with the contents provided |
| `configTxtAppend` | Append the contents provided to the `config.txt` file               |
