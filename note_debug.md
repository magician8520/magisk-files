## Magisk-delta (8fd6e293) DEBUG by HuskyDG

- Restore MagiskHide functionality. MagiskHide can be enabled with or without Zygisk. After enable MagiskHide, apps in DenyList will still have Zygisk module loaded
- Advanced hiding for MagiskHide: Allow MagiskHide to handle isolated process when Zygisk is enabled
- Clean up preload when hiding with MagiskHide
- The package name is `io.github.huskydg.magisk`
- MagiskHide option does not affect Enforce DenyList option in database
- Fix checked box of Recovery Mode option doesn't finding recovery image on direct install

## Magisk (9183a0a6) (25101)

- Sync to public release

## Diffs to v25.1

- None