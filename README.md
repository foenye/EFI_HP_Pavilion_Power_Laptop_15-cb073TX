This EFI was created with reference to the [OCLP-X](https://github.com/JeoJay127/OCLP-X) guidelines.

The Ventura-AirportItlwm.kext V2.3.0 used for WiFi requires a patch.

#### Supported os:
  - macOS Sequoia 15.7.x
#### Summaries:
  - Opencore v1.0.6
  - Patched model: MacBookPro15,1 (Prerequisites for macOS 14+)
#### Usage steps:
  - Install Sequoia normally or on an existing Sequoia macOS.
  - Replace with this EFI
  - Download and install [OCLP-X OpenCore-Patcher.pkg](https://github.com/JeoJay127/OCLP-X/releases) on your Sequoia
  - Run OpenCore-Patcher.app execute `Post-Install Root Patch` -> `Start Root Patching` (When you see: Available patches for your system: Networking: Intel WiFi)
  - After restarting, WiFi and Bluetooth are now working.
  - Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to generate new valid information by modifying config.plist. (When you login Apple ID, [OpenCore-Install-Guide#PlatformInfo](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake.html#platforminfo))
