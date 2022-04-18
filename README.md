# Additional Stuffs Module for MagiskOnWSA
MagiskOnWSA based Magisk module

## What is this?
It's a personal demonstrational module that
trying to adding some required stuffs for my daily use

## What is included?
1. AtvRemoteService
Which is pulled-out from [OpenGapps](https://opengapps.org/)' Android TV Gapps tvstock package
for supporting Bluetooth controllers pairing to Android games.

2. Keymapping changes for Nintendo layout Controllers
Default layout for Controllers are Xbox based.
So It's messed up my Nintendo layout Controllers.
hanged file is virtual_gamepad.kl

Key mappings have changed to
```key 0x131 BUTTON_A
key 0x130 BUTTON_B
key 0x134 BUTTON_X
key 0x133 BUTTON_Y```

If you're using Xbox layout Controller or anything else,
Remove system/vendor/usr/keylayout/virtual_gamepad.kl file in this module.

3. System Properties and Sepolicy Rule
All of them are trying to improve performance (hopefully...)
These are tested on actual Android devices but not sure it's working on WSA
Checkout the commit messages for more infos.

##
That's all nothing else :)
