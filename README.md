# Rota

为独立教师、私教和音乐教师设计的排课、学生与收支管理桌面应用。

![Rota 真实排课界面](https://songhaifan.github.io/rota/rota-app.png)

课程、学生档案和收款记录都在一个清晰的工作台里。支持中文与 English，不登录也能使用；注册账号后可以同步课程信息。

v0.2.0 新增友好的首次启动流程、登录/注册入口、初始工作室设置与可重新查看的新手指引。

## 下载

- [下载最新 macOS 版本](https://github.com/SonghaiFan/rota/releases/latest)
- [打开 Rota 网页版](https://rota-two-psi.vercel.app)
- [查看完整产品页面](https://songhaifan.github.io/rota/)

当前版本支持 Apple Silicon Mac（M1、M2、M3、M4 及后续芯片），最低系统版本为 macOS 12。

## 安装

1. 在 Releases 页面下载最新的 `Rota-0.2.0-arm64.dmg`。
2. 打开 DMG，把 Rota 拖入“应用程序”文件夹。
3. 当前测试版尚未使用 Apple Developer 证书签名。如果 macOS 阻止首次打开，请在“系统设置 → 隐私与安全性”中选择“仍要打开”。

## 云同步

Rota 支持注册账号并同步课程信息。账号和云端课程数据由 Rota 的 Supabase 项目保存。

## 文件校验

SHA-256 校验值见 [CHECKSUMS.txt](./CHECKSUMS.txt)。

> 此仓库仅用于分发 Rota 桌面版，不包含应用源代码。
