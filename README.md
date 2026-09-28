# ScrapeFun Client for macOS

[产品主页](https://github.com/HaoweiLi97/ScrapeFun) · [稳定版下载](https://github.com/HaoweiLi97/scrapefun-client-macos/releases/latest) · [全部发行](https://github.com/HaoweiLi97/scrapefun-client-macos/releases) · [在线文档](https://scrapefun.com/#/docs)

> 文档更新：2026-09-28。下列版本和资产为核对当日的稳定版；后续以对应 Release 为准。

macOS 桌面客户端，连接已有 ScrapeFun Server，浏览和播放影视资源，也可阅读漫画。Client 的安装不需要在这台 Mac 上同时部署 Server。

## 下载与系统环境

| 项目 | 当前稳定版 |
| --- | --- |
| 版本 | [0.0.4](https://github.com/HaoweiLi97/scrapefun-client-macos/releases/tag/v0.0.4) |
| 架构 | Apple Silicon / arm64 |
| 手动安装 | `.dmg` |
| 更新资产 | `.zip`、`.blockmap`、`latest-mac.yml` |

从[稳定版下载页](https://github.com/HaoweiLi97/scrapefun-client-macos/releases/latest)获取 DMG。当前 Release 未提供 Intel 安装包；系统要求与签名状态以该版说明和安装包为准。

## 安装

1. 打开 DMG，将 `ScrapeFun Client.app` 拖入“应用程序”。
2. 从“应用程序”启动客户端。
3. 如果系统阻止启动，先核对来源、架构和具体 Release 的首次启动说明。

ZIP、blockmap 和 YAML 用于更新分发；手动首次安装优先使用 DMG。

## 连接 Server

填写 Server 地址，例如 `http://192.168.1.10:8096`，使用该 Server 的账号登录。跨设备连接时，Server 需允许相应网络访问；`localhost` 只指当前 Mac。

## 更新与配置

可使用客户端更新机制，或下载新版 DMG 后覆盖安装。同一用户下更新通常保留连接设置；不要删除用户配置目录。更新 Client 不替代 Server 升级，Server 的媒体库和业务数据需另行备份。

## 故障排查

报告问题时提供 macOS 版本、Mac 架构、Client 与 Server 版本及复现步骤。安装错误附系统提示，播放错误附脱敏日志和媒体编码信息。

## 支持与授权

本仓库提供平台安装说明和官方发行资产。使用问题与功能建议请提交到[主仓库 Issues](https://github.com/HaoweiLi97/ScrapeFun/issues)；账号、激活或私密日志请联系 `scrapefun@outlook.com`。报告安全问题请按[安全说明](./SECURITY.md)私密提交。

新的商业许可声明见 [LICENSE](./LICENSE)，完整条款见[软件使用许可协议](./EULA.md)。个人、家庭及组织内部可正常使用；Pro 需有效授权，软件再分发、转售、客户交付和收费托管须单独书面授权。该声明不追溯改变既有授权；现有资产以其随包许可为准，第三方组件继续适用各自许可证。

[发行与兼容性说明](https://github.com/HaoweiLi97/ScrapeFun/blob/main/RELEASE_POLICY.md) · [第三方组件说明](https://github.com/HaoweiLi97/ScrapeFun/blob/main/THIRD_PARTY_NOTICES.md) · [支持流程](./SUPPORT.md)
