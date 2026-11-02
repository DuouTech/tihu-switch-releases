# Tihu-Switch 官方发行

当前正式版：[Tihu-Switch 1.0.0](https://github.com/DuouTech/tihu-switch-releases/releases/tag/v1.0.0)。下载 [Windows x64 当前用户级安装包](https://github.com/DuouTech/tihu-switch-releases/releases/download/v1.0.0/Tihu-Switch_1.0.0_x64-setup.exe)。

安装包 SHA256：`9b02e731eec799e5cfef48b499f727de2f030326b7a6becaa4c08103fddcb8a6`。公开安装器及签名已经匿名下载核对，并通过独立 Tauri/minisign 验签；[stable 更新清单](https://raw.githubusercontent.com/DuouTech/tihu-switch-releases/main/channels/stable/latest.json)使用 Tihu 独立签名及发行源。安装器没有 Windows Authenticode 发布者证书签名，minisign 不等于 Authenticode。

Tihu 使用独立应用身份、`.tihu-switch` 资料目录和 `tihu-switch://` 协议，默认本地路由端口为 15723。与 Duou 共存时，接管同一个 Agent 前须先退出原路由或明确释放控制权；释放会保留原文件，不等于已恢复直连。启用新配置仍由用户明确操作。

当前平台的网页免填授权保持关闭，尚未完成受支持环境下的完整验收。可使用已验证的手动路径：安装 Tihu → 选择 Agent → 填写平台地址和自己保存的 Key → 获取实际可用模型并检测 → 保存 → 明确启用。保存配置不会自动接管 Agent；连接检测可能产生调用费用。参见[平台接入指南](https://api.tihujianzhi.com/buy/keys#guide)。

本仓库仅提供安装包、更新清单、校验和、发布说明和必要许可。私有应用源码、用户配置和凭据不在本仓库；GitHub 自动生成的源码归档仅包含这个公开发行仓库。仅发布 Windows x64，测试候选不是日常安装包。

Tihu-Switch 与 Duou-Switch 共用一个固定核心，保留 CC Switch 的 MIT 许可、作者版权和第三方署名。
