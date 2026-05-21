# KernelSU-Next for OnePlus 9R running LineageOS 23 or Evolution X 11.6.

**English** | [简体中文](README_CN.md)

## Features
- LineageOS 23.2 kernel source with KernelSU-Next.

## Devices
- OnePlus 9R currently running LineageOS 23.2 or Evolution X 11.6.

## Usage
- Make sure your device bootloader is unlocked and already flashed OFFICIAL LineageOS 23 or Evolution X 11.6.
- Type `adb reboot recovery` in adb command line or manually reboot to recovery mode.
- Tap "Apply update" > "Apply from ADB", then type `adb sideload path\to\your\kernel.zip` in adb command line, reboot to system when process done.
- Install [Official KernelSU Next Manager](https://github.com/KernelSU-Next/KernelSU-Next/releases/latest)。

## Notes
- This kernel has currently only been tested on the two custom ROMs based on Android 16 I mentioned above. Feel free to test on other custom ROMs your own.

## Known Issues
- You tell me.

## Downloads
- [Releases](https://github.com/LenseTech/android_kernel_oneplus_sm8250-lineage-23.2_KernelSU-Next/releases/latest).

## Credits
- [KernelSU](https://github.com/tiann/KernelSU/), [KernelSU-Next](https://github.com/KernelSU-Next/KernelSU-Next): The powerful root tool.
- [LineageOS/android_kernel_oneplus_sm8250](https://github.com/lineageos/android_kernel_oneplus_sm8250): Original kernel source.

Sorry for my poor English ;)
