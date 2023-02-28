# Anycubic Kobra Neo Tweaked Firmware

This is a fork of the publicly released Kobra Neo firmware version 1.3.3. It appears that newer firmwares from the vendor hinder the ability to output messages to the LCD.

Performining minor adjustments for quality of life improvements. Most of these are centered around Octoprint messaging functionality.

- Enable M117 codes to allow Octoprint to send messages to the LCD
- Enable M73 codes to allow updating the LCD progress bar from Octoprint
- ~~Enabled Square wave stepping for print quality~~
- Linear Advance is **not** enabled
- version number will read 1.3.3a as a visual indicator of accepted firmware

This firmware contributes very little if anything to print quality.  If your prints are working as expected, and you're not looking to use Octoprint plugins to display custom messages, use the official firmware from Anycubic.

