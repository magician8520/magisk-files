## Magisk-delta (3a26fc41) by HuskyDG

> Debug version might unstable. Do not use if not needed

- Restore MagiskHide functionality. MagiskHide can be enabled with or without Zygisk. After enable MagiskHide, apps in DenyList will still have Zygisk module loaded
- Advanced hiding for MagiskHide: Allow MagiskHide to handle isolated process when Zygisk is enabled
- Clean up preload when hiding with MagiskHide
- The package name is `io.github.huskydg.magisk`
- MagiskHide option does not affect Enforce DenyList option in database
- Fix checked box of Recovery Mode option doesn't finding recovery image on direct install

## Magisk upsteam to commit 71205bc (25001)

- Update hijack bins
- Fix update in recovery patch mode
- Update ramdisk restore implementation
- Better network detection and invalidation
 