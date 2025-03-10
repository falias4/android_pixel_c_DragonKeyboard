# The issue

When using the Pixel C with the official physical keyboard on a custom ROM, then the keys might not be correctly mapped.
Examples:
  * German: Key for letter `Ü`
  * Norwegian: Key for letter `Å`

# Solution

This project is a simple standalone build of the [DragonKeyboard](https://github.com/LineageOS/android_device_google_dragon) from the LineageOS for the Pixel C.\
It simply adds the missing (correct) layouts for your keyboard.

# How to use

1. Download latest version from releases
2. Install on your device
    * E.g.: `adb install <path_to_apk>`
3. On your device go to `Settings > System > Languages & Input > Physical keyboard`
4. Select the `Pixel C Keyboard`
6. Choose one of the new layouts prefixed with `#PixelC | `

# Additional notes

Only tested with LineageOS 20.0.\
See also [XDAForums - [ROM] [13.0] [Dragon] LineageOS 20.0 [UNOFFICIAL]](https://xdaforums.com/t/rom-13-0-dragon-lineageos-20-0-unofficial.4540725/).
