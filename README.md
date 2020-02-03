TWRP Device Tree for begonia

## Features

Works:

- ADB
- Decryption of /data
- Screen brightness settings
- Correct screenshot color
- MTP
- Flashing (opengapps, roms, images and so on)
- Backup/Restore (Needs more testing)
- USB OTG
- Android Q Support
- OTA support for Begoniain (01032020)

TO-DO:

- Comes later...

##
3 kernels are included.

MIUI 10 Pie kernel (Image.gz-10)
MIUI 11 Pie Kernel Included (Image.gz)
Android 10 kernel included (image.gz-Q)
## Compile

First checkout minimal twrp with omnirom tree:

```
repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0
repo sync

Finally execute these:

. build/envsetup.sh
lunch omni_begonia-eng
mka recoveryimage ALLOW_MISSING_DEPENDENCIES=true # Only if you use minimal twrp tree.

## Other Sources


## Thanks

wzsx150
AgentFabulous : https://github.com/AgentFabulous
