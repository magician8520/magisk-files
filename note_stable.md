## Magisk-delta v25.1 by HuskyDG

- Restore MagiskHide functionality. MagiskHide can be enabled with or without Zygisk. After enable MagiskHide, apps in DenyList will still have Zygisk module loaded
- Advanced hiding for MagiskHide: Allow MagiskHide to handle isolated process when Zygisk is enabled
- Clean up preload when hiding with MagiskHide
- The package name is `io.github.huskydg.magisk`
- MagiskHide option does not affect Enforce DenyList option in database

## Magisk v25.1 Official changes

- [MagiskBoot] Fix ramdisk backup being incorrectly skipped
- [MagiskBoot] Add new feature to detect unsupported dtb and abort during installation
- [Zygisk] Change binary hijack paths
- [App] Fix incorrect recovery mode detection and installation
- [MagiskInit] Fix config not properly exported in legacy SAR devices
- [General] Enforce the Magisk app to always match or be newer than magiskd
