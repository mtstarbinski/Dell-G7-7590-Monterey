Bassed on: https://github.com/Juan-VC/Hackintosh-macOS-Dell-G7-7588

This is a release build assuming that CFG Lock has been disabled.

To boot without CFG Lock being disabled, AppleXcpmCfgLock must be set to True in the config.plist.

To enable CFG Lock after bios reset, boot into modGRUBShell.efi and run `setup_var 0x5C4 0x00`.
