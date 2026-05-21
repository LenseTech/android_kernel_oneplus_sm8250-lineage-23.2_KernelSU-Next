# 适用于一加9R LineageOS 23.2/Evolution X 11.6 的KernelSU Next内核

[English](README.md) | **简体中文**

## 功能
- 集成了KernelSU Next的LineageOS 23.2内核。

## 适用设备
- 当前运行Evolution X 11.6或LineageOS 23.2的一加9R。

## 使用方法
- 确保Bootloader已经解锁且已经刷入官方LineageOS 23.2或Evolution X 11.6。
- 在adb命令行输入`fastboot reboot recovery`或手动重启到recovery模式。
- 进入adb sideload模式，使用`adb sideload 你存放压缩包的路径.zip`，刷完后重启手机。
- 安装[官方KernelSU Next管理器](https://github.com/KernelSU-Next/KernelSU-Next/releases/latest)。

## 注意事项
- 该内核目前仅在我上面提到的两个安卓16版本的类原生中测试通过，其他系统未测试。

## 已知问题
- 暂未发现。

## 下载
- 请转到[发行版](https://github.com/LenseTech/android_kernel_oneplus_sm8250-lineage-23.2_KernelSU-Next/releases/latest)下载。

## 鸣谢
- [KernelSU](https://github.com/tiann/KernelSU/), [KernelSU-Next](https://github.com/KernelSU-Next/KernelSU-Next)：强大的Root工具。
- [LineageOS/android_kernel_oneplus_sm8250](https://github.com/lineageos/android_kernel_oneplus_sm8250)：基于此内核源码编译。
