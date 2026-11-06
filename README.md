# +1安全系统 · 官方下载与更新源

本仓库是 **+1安全系统** 的公网 **下载站** 与 **在线更新库**。

客户端「检查更新」从本仓库的 [GitHub Releases](https://github.com/m63058037/Plus1Security-Updates/releases) 读取 `update.json` 并下载安装包；你也可以在 Releases 页面手动下载最新安装包。

## 本仓库提供什么

| 内容 | 说明 |
|------|------|
| 安装包 zip | 含 `Plus1Security-Setup.exe` 与 `payload\`，可全新安装或覆盖升级 |
| `update.json` | 客户端更新通道元数据（版本、校验、下载地址） |
| 版本说明 | 各 Release 附带本版变更摘要 |

## 本仓库不提供什么

- **不提供任何产品源代码**（C# / 脚本 / 工程文件等均不在此仓库）
- **不提供开发文档、内部架构说明或可复现构建树**
- 本仓库定位为 **发行与分发**，不是开源镜像

产品对发行包采取 **半开放** 策略：更新与安装包可公开获取，便于终端直更；**核心实现仍不开放源码**。详见根目录 [`LICENSE`](LICENSE)。

## 如何下载 / 更新

1. **终端用户（已安装）**  
   打开 +1安全系统托盘 → **检查更新** → 按提示一键升级。

2. **手动下载**  
   打开 [Releases](https://github.com/m63058037/Plus1Security-Updates/releases/latest) → 下载 `Plus1Security-Setup-Pack-vX.Y.Z.zip` → 解压后运行 `Plus1Security-Setup.exe`（需按提示确认管理员权限）。

3. **开发 / 发行方**  
   仅通过已审核发布目录经官方脚本上传；未审核包不会进入本仓库。

## 最新通道

- 更新元数据：  
  `https://github.com/m63058037/Plus1Security-Updates/releases/latest/download/update.json`
- 最新发行页：  
  https://github.com/m63058037/Plus1Security-Updates/releases/latest

## 安全与信任

- 请只从本仓库 Releases 或官方 U 盘引导目录获取安装包。
- 客户端会对更新包做哈希校验（见 `update.json` 中的 `sha256`）。
- 勿信任来历不明的第三方「破解包 / 绿化包」。

## 许可

分发与使用受 [`LICENSE`](LICENSE)（+1安全系统 L 许可证）约束。本仓库 **不是** OSI 意义上的开源软件仓库。

---

© +1安全系统 · Plus1Security
