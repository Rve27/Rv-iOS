- **Support for AOSP/LOS/PixelStock and Closest Kin Like ROMS/~~Oxygen/Miui-HyperOS/Samsung(OneUI5)~~**
- **Android 12/13/14 ready**
- **Compatible with Magisk and KSU**

# Important Info Before Installation:
As of new changes the installation logic has changed dated: `11/22/2023` for seamless installation across KSU/Magisk/Newer android versions. With no font or font related module (that modifies `fonts.xml`) installed (if installed any uninstall all of them and reboot) open any Terminal app eg. `Termux` run this following command with root permission. 
```
su -c '
[ ! -d /sdcard/MFFM/fontsxml ] && mkdir -p /sdcard/MFFM/fontsxml
cp /system/etc/fonts.xml /sdcard/MFFM/fontsxml/fonts.xml
cp /product/etc/fonts_customization.xml /sdcard/MFFM/fontsxml/fonts_customization.xml'
```
You only need to do this once. Repeat this only if you change ROM! After this you are ready to install, update, dirty install, install `MFFMv12` modules without any trouble. 

## iOS Emoji
 - Download iOS Emoji [here](https://raw.githubusercontent.com/Rve27/iOS/main/iOS%20Emoji/Emoji-iOSEmoji.ttf)
 - Move `Emoji-iOSEmoji.ttf` to `MFFM Folder (/LocalStorage/MFFM)`
 - Download the Emoji Addon from [here](https://github.com/Rve27/iOS/releases/download/Addon/MFFM_UniEmoji_v5.5.sh). Put it inside the `MFFM Folder (/LocalStorage/MFFM)` folder alongside the renamed emoji file.

# GApps Font
- If your Google Apps font don't change by default then flash [KillGMSFont](https://github.com/MrCarb0n/killgmsfont) Magisk Module by [MrCarb0n](https://github.com/MrCarb0n/)

# Credits
- [Magisk](https://github.com/topjohnwu/Magisk) | [Inter Font Pack By kdrag0n](https://github.com/kdrag0n/inter-font-pack) | [Template by MFFM](https://github.com/charityrolfson433/mffmv11)

# Tributes & Acknowledgements
- [OMF](https://gitlab.com/nongthaihoang/oh_my_font) | [OMF Template](https://gitlab.com/nongthaihoang/omftemplate) | [CFI](https://github.com/nongthaihoang/custom_font_installer) | [Noto Emoji Plus](https://gitlab.com/MrCarb0n/NotoEmojiPlus_OMF) | [KillGMSFont](https://github.com/MrCarb0n/killgmsfont) | [Magifont](https://t.me/Magifonts_Support)