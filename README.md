# Moto Dolby G Pro Audio FX Magisk Module

## Descriptions
- An equalizer ported from Motorola Moto G Plus (sofiap_sprout).
- No dynamic partitions

## Requirements
- Android 9, 10, or 11 devices
- 64 bit
- Magisk installed

## Guide
- Remove another Dolby module
- Reboot
- Install this module via Magisk Manager only
- Reboot

## Troubleshooting
- If SE policy patch doesn't work for your device, send logcats to dev, then try using force permissive method.
  Run at Terminal Emulator before flash:

  `su`

  `setprop dolby.force.permissive 1`

- If Dolby force close, just reinstall again
- Make sure manifest.xml is patched correctly
- Use Audio Compatibility Patch if you encounter processing problem.

## Optional
- Install Audio Modification Library module or [ACDB module](https://t.me/viperatmos) (Android 10 and bellow only) (choose one, don't use both!) if you using multiple audio mods together with Viper or Waves Maxx or any else.
- You can rename dax-default extension to .xml to use more bass enhancer boost. See /data/adb/modules_update/MotoDolby/system/vendor/etc/dolby/.

## Attention!
- Always make nandroid backup before install or updating version, these are just experiments!
- Special thanks to all people that helped and tested my modules.
- Reporting without send full logcats and install process logs is ignored!
https://play.google.com/store/apps/details?id=com.dp.logcatapp

## Telegram
- https://t.me/audioryukimods
- https://t.me/joinchat/E-On6U9cxckhIlAnoPIYpw
- https://t.me/modsandco

## Donate
- https://www.paypal.me/reiryuki

## Download
- Link bellow at "Releases"



