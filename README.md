# Charybdis 4x6 ZMK Firmware

Personal ZMK firmware for a Charybdis 4x6 wireless split keyboard with PMW3610 trackball. Aliexpress clone running SuperMini nRF52840 controllers.

Forked from [nophramel/charybdis_zmk](https://github.com/nophramel/charybdis_zmk) with a custom shield definition to match this board's matrix wiring.

## Trackball

- **CPI**: 2400 with 1/2 scale divisor (effective 1200 DPI)
- Only active on the Nav layer
- Hold the key between LCLK/RCLK on Nav to scroll

## Home Row Mods

[urob's timeless home row mods](https://github.com/urob/zmk-config) in CAGS order for macOS.

## Editing

Use the [keymap editor](https://nickcoutsos.github.io/keymap-editor/) for binding changes, or edit `config/charybdis.keymap` directly for structural stuff.

## Credits

- [nophramel](https://github.com/nophramel/charybdis_zmk) - Base config
- [badjeff](https://github.com/badjeff) - PMW3610 driver, input behavior listener, split peripheral input relay
- [petejohanson](https://github.com/petejohanson) - ZMK pointers branch
- [urob](https://github.com/urob/zmk-config) - Timeless home row mods
- [nickcoutsos](https://github.com/nickcoutsos/keymap-editor) - Keymap editor
