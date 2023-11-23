# ZMK Personal Configurations

Welcome to my personal ZMK configurations!

## Introduction

These are my custom ZMK configurations for my keyboard setup. Feel free to explore and adapt them to suit your needs.

## Getting Started

### Prerequisites

This repository leverages GitHub Actions to automatically build the firmware files. You can find the artifacts in the Actions tab of this repository. All you need is your text editor of choice to make changes.

## Configuring Your Keyboard

### Keymap

Adjust the relevant keymap configuration in `config/*.keymap` to define the function of each key on your keyboard.

You can find my daily keymap [here](config/base_lower.keymap)

## Automated Build and Flash

The firmware is automatically built using GitHub Actions. Once built, it is uploaded as an artifact. No manual building is required.

To flash them connect a compatable keyboard and enter bootloader mode, then drag and drop the relevant uf2 files. 

## Support

For more information you can view the ZMK docs [here](https://zmk.dev/docs/development/documentation)

If you have any questions or need assistance, feel free to reach out.

Happy typing!
