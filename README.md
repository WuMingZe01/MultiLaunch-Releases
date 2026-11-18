# 多开管家 · Windows 下载

多开管家在一台 Windows 电脑上管理各自独立的 WorkBuddy 账户环境。

[下载最新安装包](https://github.com/WuMingZe01/MultiLaunch-Releases/releases/latest)

1. 打开下载页，在 **Assets** 中选择 `MultiLaunch-Setup-*-win-x64.exe`，双击安装。
2. 支持 Windows 10/11 x64，需要 .NET Framework 4.8 和 Microsoft Edge WebView2 Runtime。安装器会提示缺项。请预先安装官方 WorkBuddy，并在各账户窗口自行登录。MCP 功能需要 Node.js 22.13 或更新版本。
3. 老用户安装时可以接续原便携版账户。安装完成后在 **设置 → 关于** 点击 **检查更新**，发现新版即可升级。

当前安装包未使用受 Windows 信任的发行者证书，首次安装可能显示未知发布者。可将安装包的 SHA-256 与 Releases 附带的校验文件比对。客户端一键更新会验证发布签名和安装包哈希。