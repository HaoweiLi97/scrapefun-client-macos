<div align="center">
  <img src="./docs/images/client-icon.png" alt="ScrapeFun Client" width="80" />
  <h1>ScrapeFun Client for macOS</h1>
  <p><strong>简体中文</strong> · <a href="./README.en.md">English</a></p>
  <p><a href="https://scrapefun.com/">官网</a> · <a href="https://github.com/HaoweiLi97/scrapefun-client-macos/releases/tag/v0.5.0">下载安装</a> · <a href="https://github.com/HaoweiLi97/scrapefun-client-macos/releases">全部发行</a> · <a href="https://scrapefun.com/#/docs">使用文档</a></p>
</div>

> 文档更新：2026-11-03。下列版本和资产为核对当日的稳定版；后续以对应 Release 为准。

macOS 桌面客户端，连接已有 ScrapeFun Server，浏览和播放影视资源，也可阅读漫画。Client 的安装不需要在这台 Mac 上同时部署 Server。

## 下载与系统环境

| 项目 | 当前稳定版 |
| --- | --- |
| 版本 | [0.5.0](https://github.com/HaoweiLi97/scrapefun-client-macos/releases/tag/v0.5.0) |
| 系统 | macOS 26.5 或更新版本 |
| 架构 | Apple Silicon / arm64 |
| 手动安装 | `.dmg` |
| 信任状态 | ad-hoc 完整性签名，未经 Apple Developer ID 签名或公证 |

从[0.5.0 手动下载页](https://github.com/HaoweiLi97/scrapefun-client-macos/releases/tag/v0.5.0)获取 DMG。当前 Release 未提供 Intel 安装包；系统要求与签名状态以该版说明和安装包为准。

## 安装

1. 打开 DMG，将 `ScrapeFun Client.app` 拖入“应用程序”。
2. 从“应用程序”启动客户端。
3. 如果系统阻止首次启动，先核对下载来源，再执行该版说明中的命令：

   ```bash
   xattr -dr com.apple.quarantine "/Applications/ScrapeFun Client.app"
   ```

   该命令移除下载隔离标记，不会增加 Apple 签名或公证。

0.5.0 仅提供 DMG 和校验文件，请手动安装；此包不通过应用内自动更新分发。

## 连接 Server

填写 Server 地址，例如 `http://192.168.1.10:8096`，使用该 Server 的账号登录。跨设备连接时，Server 需允许相应网络访问；`localhost` 只指当前 Mac。

## 更新与配置

0.5.0 请下载指定版本的 DMG，退出客户端后覆盖安装。同一用户下更新通常保留连接设置；不要删除用户配置目录。更新 Client 不替代 Server 升级，Server 的媒体库和业务数据需另行备份。

<details>
<summary>故障排查</summary>

报告问题时提供 macOS 版本、Mac 架构、Client 与 Server 版本及复现步骤。安装错误附系统提示，播放错误附脱敏日志和媒体编码信息。

</details>

## 支持与授权

本仓库提供平台安装说明和官方发行资产。使用问题与功能建议请提交到[主仓库 Issues](https://github.com/HaoweiLi97/ScrapeFun/issues)；账号、激活或私密日志请联系 `scrapefun@outlook.com`。报告安全问题请按[安全说明](./SECURITY.md)私密提交。

新的商业许可声明见 [LICENSE](./LICENSE)，完整条款见[软件使用许可协议](./EULA.md)。个人、家庭及组织内部可正常使用；Pro 需有效授权，软件再分发、转售、客户交付和收费托管须单独书面授权。该声明不追溯改变既有授权；现有资产以其随包许可为准，第三方组件继续适用各自许可证。

[发行与兼容性说明](https://github.com/HaoweiLi97/ScrapeFun/blob/main/RELEASE_POLICY.md) · [第三方组件说明](https://github.com/HaoweiLi97/ScrapeFun/blob/main/THIRD_PARTY_NOTICES.md) · [支持流程](./SUPPORT.md)
