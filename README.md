# ZMK Nano 33 Ble Module
This module adds a ZMK board definition for the Nano 33 Ble

# Untested Features
- Leds
  - one led is a ws2812b so an additional driver will be needed, but i don't know which pin is connected to it
- Studio support
- There is no voltage divider for the battery so zmk,battery-nrf-vddh will need to be used, but i haven't tested it yet

Documentation for the board: https://wiki.icbbuy.com/doku.php?id=developmentboard:ble-33

Partly taken and modified from https://github.com/badjeff/zmk-config/tree/main/config/boards/arm/nologo_nano33_ble
