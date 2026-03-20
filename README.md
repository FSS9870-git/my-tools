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

## 📜 开源与来源声明
本仓库为个人工具集合，其中部分内容引用自开源项目或社区分享：
- **LSPosed**：项目地址 [https://github.com/LSPosed/LSPosed](https://github.com/LSPosed/LSPosed)，版权归原作者所有，本仓库仅提供便捷下载，使用需遵循其开源协议。
- **uXuexitongJS**：为社区分享的学习通辅助脚本，版权归原作者所有，本仓库仅作个人学习备份，请勿用于商业用途。
- **adb**：为 Google 官方 Android SDK 平台工具，遵循 Android SDK 许可协议。

我尊重原作者的知识产权与开源精神，若涉及侵权，请联系我进行删除。

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
- 刷课详细使用教程请访问：https://github.com/unraous/uXuexitongJS
