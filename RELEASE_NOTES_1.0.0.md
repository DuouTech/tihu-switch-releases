# Tihu-Switch 1.0.0

正式资产、发布日期和校验和以本仓库对应的 GitHub Release 为准。

Tihu-Switch 是独立的 Windows x64 客户端，与 Duou-Switch 共享核心，保留 Agent 与通用供应商配置、MCP、Skills、会话、授权、用量统计和词元小票等既有能力。

本版提供鹈鹕平台快速接入和新的绿野玻璃默认主题，保留原有五种主题。配置先保存，用户明确启用后才写入 Agent；模型与服务可用性以账户权限和当前供给为准。

Tihu 使用独立的安装身份、资料目录、深链和更新签名，不自动迁移 Duou 的凭据或账户。两款应用可独立安装；如需管理同一个 Agent，应先停止原应用对此 Agent 的路由并释放控制权，再在另一应用启用。

支持范围为 Windows x64。安装包签名文件用于 Tauri/minisign 更新校验，不等同于 Windows Authenticode 发布者证书。
