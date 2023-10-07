# USBCDEV Pmod™ Compatible Module

This is a simple USB-C module for developing certain USB-C devices directly in FPGA gateware. Note that it’s not possible to precisely meet the USB specs with this PMOD but it might be close enough for your purposes, please check the schematics and layout.

This repo contains PCB layouts, schematics and pinouts.

Find more information on the [product page](https://machdyne.com/product/usbcdev-pmod/).

## Pinout

| Pin | Signal |
| --- | ------ |
| 1 | USB\_DP |
| 2 | USB\_DN |
| 3 | USB\_DP\_PU |
| 4 | USB\_DN\_PU |
| 5 | GND |
| 6 | 3V3 |

## License

The contents of this repo are released under the [Lone Dynamics Open License](LICENSE.md) with the following exceptions:

- The KiCad design files contain parts of the [kicad-pmod](https://github.com/mithro/kicad-pmod) library which is released under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html).

- The KiCad design files may contain symbols and footprints released under other licenses; please contact us if we've failed to give proper attribution.

Note: You can use these designs for commercial purposes but we ask that instead of producing exact clones, that you either replace our trademarks and logos with your own or add your own next to ours.
