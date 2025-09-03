# Zephyr Mechanical Keyboard (ZMK) Firmware for Steelseries Apex Pro Mini

This is a ZMK fork for the Steelseries Apex Pro Mini keyboard.

## Build

    west build zmk/app/ -p always -b nice_nano_v2 -- -DSHIELD=kyria_left
