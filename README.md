# Treble Overlay for Xiaomi Poco F4 GT

This Magisk module places the Treble Overlay on `/system/product/overlay`, since `/system` is read-only on Magisk systems.

All overlays can be found in [TrebleDroid's repository](https://github.com/TrebleDroid/vendor_hardware_overlay).

Source for Xiaomi Poco F4 GT overlay can be found in [my own repository](https://github.com/Le0xFF/vendor_hardware_overlay).

## Using this Module

1. Download the latest release from the [releases tab](https://github.com/Le0xFF/treble-overlay-xiaomi-pocof4gt/releases/latest)
2. Move it to your device (through `adb push` for example)
3. Install the module using Magisk

## Building

You can use the provided APK from the repo, or replace it with a modified overlay.

To generate the zip file for Magisk, run

``` sh
make
```

You must be running a Linux system and have `make` installed. Otherwise, you can zip the files manually.

### Cleaning Up

To delete the generated artifacts, run

``` sh
make clean
```
