## Magisk (198dd633) by HuskyDG

> Debug version might unstable. Do not use if not needed

- Restore MagiskHide functionality. MagiskHide can be enabled with or without Zygisk. After enable MagiskHide, apps in DenyList will still have Zygisk module loaded
- Advanced hiding for MagiskHide: Allow MagiskHide to handle isolated process when Zygisk is enabled
- Clean up preload when hiding with MagiskHide
- The package name is `io.github.huskydg.magisk`
- MagiskHide option does not affect Enforce DenyList option in database

## Magisk upsteam to commit 71205bc (25001)

- Update hijack bins
- Fix update in recovery patch mode
- Update ramdisk restore implementation
- Better network detection and invalidation
 