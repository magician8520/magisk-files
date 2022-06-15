## Magisk-delta v24.3 by HuskyDG

- Restore MagiskHide functionality. MagiskHide can be enabled with or without Zygisk. After enable MagiskHide, apps in DenyList will still have Zygisk module loaded
- Advanced hiding for MagiskHide: Allow MagiskHide to handle isolated process when Zygisk is enabled
- Clean up preload when hiding with MagiskHide
- The package name is `io.github.huskydg.magisk`
- MagiskHide option does not affect Enforce DenyList option in database

## Magisk v24.3 Official changes

- [General] Stop using getrandom syscall
- [Zygisk] Update API to v3, adding new fields to AppSpecializeArgs
- [App] Improve app repackaging installation workflow

