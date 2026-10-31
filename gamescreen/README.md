# 单屏助手

当前版本：**2.5.4**。适用于Windows 10/11。

- [下载便携版](https://github.com/zhouyou0082-lgtm/ops-workbench-updates/raw/refs/heads/main/gamescreen/releases/2.5.4.0/GameScreen-2.5.4-portable.zip)
- [下载单文件程序](https://github.com/zhouyou0082-lgtm/ops-workbench-updates/raw/refs/heads/main/gamescreen/releases/2.5.4.0/GameScreen.exe)
- [本次更新说明](releases/2.5.4.0/release-notes.txt)

已安装的用户可在 **设置 → 线上更新 → 检查更新 → 下载并更新**。游戏运行期间暂缓安装；安装过程保留用户配置、游戏列表及统计。

2.5.4新增星核跃迁电影版，保留原四款光效，支持自定义欢迎名称、无游戏预览、独立音效开关及音量。光效与声音随程序离线提供。

外接显示器亮度新增DDC/CI兼容指令和写后回读确认；未确认时显示实际反馈和排查提示。请在显示器自己的菜单开启DDC/CI。HDR、显示器模式或连接设备可能限制硬件亮度控制，具体显示器仍需实测。

保留横竖屏遮罩、软件音量和专属输出设备、自动游戏准备、恢复及签名更新。

## 下载与更新

程序仅接受原发布密钥签名的单屏助手清单，下载后验证大小、SHA256、产品和版本，启动自检失败时尝试回退。

更新通过GitHub官方API、原始文件和网页下载入口自动尝试备用线路，不需要GitHub账号，也不在程序中内置GitHub令牌。当前没有国内下载服务器，无法保证所有地区及运营商都能直连；访问失败时请稍后重试。

## 使用

解压便携版后启动GameScreen.exe，可按引导安装到当前Windows用户目录。配置和统计保存在本机用户数据目录，分发包不包含维护者的配置、统计、源码、发布私钥或第三方补帧软件。

游戏准备页可选择开场光效、名称与音效；首页及托盘的“预览开场”不启动游戏或执行系统配置调整。

亮度设置需要显示器和连接支持硬件控制；程序不会在失败时静默改动HDR或显卡Gamma。音频输出切换也受软件自身设备重建方式影响，固定占用设备的游戏可能需要在游戏内重选输出或重启。

## 光效许可

原四款Light Pillar效果来自React Bits，Copyright (c) 2026 David Haz，MIT + Commons Clause，完整许可保存在软件“光效来源与许可”。星核跃迁电影版的光效编排与声音由本项目制作。

本目录使用独立的`gamescreen/latest.json`更新清单，与同仓库其他软件的Release更新入口独立。
