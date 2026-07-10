# 10-July-2026

- Battery cycle count no longer shows unavailable
- Enable 60 fps video record suporte in Aperture
- Move region variant props selection to SKU props
- Dropped useless Xiaomi displayfeature
- Added soundtrigger HAL
- Moved to AOSP WFD service
- Remove custom Kernel Clang Flags now we use whatever AOSP decides
- Switched main partitions to EROFS filesystem(‼️ This requires flashing new boot and vendor_boot images first only then you can sideload new Rom)
- Pinned Launcher and WebView in memory for faster app launching
- Switched to AOSP offline charging daemon
- Enabled support for all filesystem types on USB-OTG drives
- Dropped support for legacy Marshmallow-era 32-bit apps
- Disabled Skia tracing by default
- Disabled EGL image tracking by default
- Downscale task snapshots to 70% to avoid memory pressure
- Synced kernel sources to **4.19.325**

# 01-July-2026

- July Pixelos Release
- Switched to AIDL camera HAL
- Switched to common Lights HAL
- Switched to generic Qualcomm SELinux policies
- Upgraded recovery and system keys to RSA-4096 for better security
- Disabled resource-heavy background blurs by default for a smoother UI
- Disabled storage checkpoint garbage collection 
- Updated Wi-Fi Display (WFD) binaries from newer device firmware fixing the previous hacks used to make it work
- Moved to ClearKey DRM service APEX for secure video streaming
- Moved recovery resources to vendor_boot partition for a cleaner structure
- Enabled kernel VINTF enforcement for better compliance
- Switched Widevine DRM dependency to a cryptographic shim
- Resolved secure video playback issues in Netflix/other Ott apps
- Cleaned up obsolete packages and unused overlays
- Configured build system to use LLVM compiler tools 
- There are many other miscellaneous bug fixes & improvements
