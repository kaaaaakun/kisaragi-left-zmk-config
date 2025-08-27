# ZMK Configuration for Kisaragi

Generated from QMK info.json

## Keyboard Information
- Name: Kisaragi
- Type: Unibody
- Normalized Name: kisaragi
- Board: ble_micro_pro

## Files Structure

### Unibody Keyboard Files
- boards/shields/kisaragi/kisaragi.overlay - Hardware definition
- boards/shields/kisaragi/kisaragi.conf - Configuration

### Common Files
- boards/shields/kisaragi/layouts.dtsi - Physical layout definition
- boards/shields/kisaragi/Kconfig.defconfig - Default configuration
- boards/shields/kisaragi/Kconfig.shield - Shield configuration
- boards/shields/kisaragi/kisaragi.zmk.yml - ZMK metadata
- boards/shields/kisaragi/kisaragi.keymap - Shield keymap include
- config/keymap.keymap - Keymap definition
- config/info.json - Keyboard layout information for keymap editors
- config/west.yml - West manifest for ZMK dependencies
- build.yaml - Build configuration for ZMK
- zephyr/module.yml - Zephyr module configuration
- .github/workflows/build.yml - GitHub Actions workflow for building firmware

## Usage
1. Copy all files to your ZMK config repository
2. Customize the keymap in config/keymap.keymap as needed
3. Push to GitHub to trigger automatic firmware builds

## Board Information
This configuration is set up for ble_micro_pro. The board is from sekigon-gonnoc's repository.
