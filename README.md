# Configuration File Readme
## General Settings
- version (integer)
  - Description: Version number of the configuration file.
  - Allowed to Configure: No
  - Default: "version": 3
- image (string)
   - Description: Filename of the image to be used.
   - Allowed to Configure: Yes
   - Default: "image": "def.png"
- show_after_drop (boolean)
  - Description: Whether to show something after a drop action.
  - Allowed to Configure: Yes
  - Default: "show_after_drop": true
- USB and File Server Settings
allow_usb_msc (boolean)
  - Description: Whether USB Mass Storage Class (MSC) is allowed.
  - Allowed to Configure: No
  - Default: "allow_usb_msc": true
- allow_file_server (boolean)
   - Description: Whether the file server functionality is allowed.
   - Allowed to Configure: No
   - Default: "allow_file_server": false
- Display Settings
  - disp_brightness (integer)
  - Description: Brightness level of the display (0-100).
  - Allowed to Configure: Yes
  - Default: "disp_brightness": 100
- Solid Color Settings
  - solid_color (object)
  - Description: Configuration for the solid color display settings.
  - Allowed to Configure: Yes
- Properties:
  - led_bits (integer): Bit mask for the LEDs to be controlled.
  - Default: "led_bits": 127
  - color (string): Color code in hexadecimal format.
  - Default: "color": "990000"
- Pattern Settings
  - activate_pattern (boolean)
  - Description: Whether a custom pattern should be activated.
  - Allowed to Configure: Yes
  - Default: "activate_pattern": true
- pattern_repeat (integer)
  - Description: Number of times the pattern should repeat.
  - Allowed to Configure: Yes
  - Default: "pattern_repeat": 3

Demo video:
https://www.youtube.com/watch?v=ikuPcvEw1WE&t=8s
