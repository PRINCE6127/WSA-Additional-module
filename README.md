# Additional Stuffs Module for MagiskOnWSA
[MagiskOnWSA](https://github.com/LSPosed/MagiskOnWSA) based Magisk module.

## WARNING
This is DEMONSTRATIONAL module!!

## What is this?
It's a personal demonstrational [Magisk](https://github.com/topjohnwu/Magisk) module that
<br>trying to adding some required stuffs for my daily use, based on [MagiskOnWSA](https://github.com/LSPosed/MagiskOnWSA)
<br>which is integrating GApps and Magisk into Windows Subsystem for Android (WSA).

## What is included?
### AtvRemoteService
Which is pulled-out from [OpenGapps](https://opengapps.org/)' Android TV Gapps tvstock package
<br>for supporting Bluetooth controllers pairing to Android games.

### Keymapping changes for Nintendo layout Controllers
Default layout for Controllers are Xbox based.
<br>So It's messed up my Nintendo layout Controllers.
<br>changed file is virtual_gamepad.kl

Key mappings have changed to
```
key 0x131 BUTTON_A
key 0x130 BUTTON_B
key 0x134 BUTTON_X
key 0x133 BUTTON_Y
```

If you're using Xbox layout Controller or anything else,
<br>Remove system/vendor/usr/keylayout/virtual_gamepad.kl file in this module.

### System Properties and Sepolicy Rule
All of them are trying to improve performance (hopefully...)
<br>These are tested on actual Android devices but not sure it's working on WSA
<br>Checkout the commit messages for more infos.

##
That's all nothing else :)
