# Logitech MX Master 3S Configuration for Linux

This repository contains a `logid.cfg` configuration file for customizing the Logitech MX Master 3S mouse on Linux using **logiops**.

## Configuration File Overview
The configuration file includes:
1. **SmartShift**: Enables automatic switching between free-spinning and ratcheted scroll modes based on movement speed.
2. **High-Resolution Scrolling**: Configures high-res scrolling behavior.
3. **Thumbwheel Settings**: Customizes the thumbwheel actions for volume control.
4. **Gesture Button Mapping**: Assigns custom actions to gestures.

### Key Names Used
Below are the key codes used in this configuration. These follow the Linux input event system standards.

#### Keys Defined in `logid.cfg`:
- `KEY_A`: Select all.
- `KEY_C`: Copy.
- `KEY_V`: Paste.
- `KEY_X`: Cut.
- `KEY_Z`: Undo.
- `KEY_VOLUMEDOWN`: Decrease Volume.
- `KEY_VOLUMEUP`: Increase Volume.
- `KEY_PLAYPAUSE`: Play/Pause Media.

#### Additional Key Names You Can Use
- `KEY_BRIGHTNESSUP` / `KEY_BRIGHTNESSDOWN`: Adjust screen brightness.
- `KEY_MUTE`: Mute audio.
- `KEY_TAB`: Simulate Tab key.
- `KEY_ESC`: Escape key.

For a full list of available key names, extract from Source: Check the input-event-codes.h file in the Linux kernel source (typically in /usr/include/linux).

## How to Use
1. Install **logiops** following the [official guide](https://github.com/PixlOne/logiops).
2. Copy the `logid.cfg` file to the configuration directory:
    '''sudo cp logid.cfg /etc/logid.cfg'''
3. Restart the logid service:
    '''sudo systemctl restart logid'''
## Customization
Feel free to edit 'logid.cfg' to suit your preferences. Refer to the comments in the configuration file for guidance.

## Contributions
Contributions are welcome! Submit a pull request if you have improvements or suggestions.

