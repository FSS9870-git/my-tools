# my-tools
我常用的工具集合

---

## 📦 工具列表

| 文件名 | 用途 | 备注 |
|--------|------|------|
| `LSPosed-v1.9.2-7024-zygisk-release.zip` | Xposed 框架模块，用于安卓模块化修改 | 需配合 Zygisk 使用，支持 Android 8.0+ |
| `adb.zip` | Android 调试桥工具包 | 用于安卓设备调试、文件传输、命令执行，包含 Windows 平台可执行文件 |
| `uXuexitongJS-master.zip` | 学习通自动刷课脚本 | 基于 JavaScript，可自动完成学习通课程视频播放、答题等任务 |

---

## ⚠️ 使用说明

### 1.adb 工具使用
- 解压 `adb.zip` 后，将目录添加到系统环境变量 `PATH`
- 打开终端/命令提示符，执行 `adb devices` 验证连接
- 常用命令：
  ```bash
  adb devices        # 查看已连接设备
  adb push 本地文件路径 /sdcard/   # 推送文件到手机
  adb shell           # 进入设备 shell

 ### 2. LSPosed 模块安装
- 需先安装 Magisk 并启用 Zygisk
- 在 Magisk 中刷入 LSPosed-v1.9.2-7024-zygisk-release.zip
- 重启设备后，通过 LSPosed 管理器安装 / 管理模块

  ### 3.uXuexitongJS 学习通刷课使用
  - 详细使用教程请访问：https://github.com/unraous/uXuexitongJS
