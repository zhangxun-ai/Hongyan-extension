# 下载与安装

[← 返回产品介绍](../README.md) · [使用教程](guide.md)

## 先确认版本

| 版本 | 当前状态 | 功能范围 |
| --- | --- | --- |
| **26.10.16.12** | 已公开发布，提供 Google 商店签名 CRX | 小红书资料采集、关键词、评论、视频与云端逐字稿、飞书／Obsidian 保存等既有功能 |
| **26.10.23.1** | 本地开发版，尚未公开发布 | 新增抖音适配、账号分析与作品对照、单篇内容解读、本地 Whisper 及新版界面 |

README 与教程介绍新版功能，当前公开包不包含上述新增能力。新版正式发布后会在同一 [Releases 页面](https://github.com/zhangxun-ai/Hongyan-extension/releases)更新；获取状态可[联系作者](https://extensions.zhangxun.org/hongyan/#wechat)确认。

## 下载入口

- **[GitHub 版本发布页](https://github.com/zhangxun-ai/Hongyan-extension/releases)**：查看更新说明及附件。
- **[下载 26.10.16.12 CRX](https://github.com/zhangxun-ai/Hongyan-extension/releases/download/v26.10.16.12/hongyan-26.10.16.12.crx)**：当前已公开的安装包。
- **[Chrome 应用商店](https://chromewebstore.google.com/detail/pjdbnlfpofkgcglogmdgplamgabooceo)**：安装前核对页面显示版本，以商店实际可用状态为准。

公开版仅提供 CRX，不提供解压版 ZIP。Google 商店签名 CRX 的扩展 ID 为 `pjdbnlfpofkgcglogmdgplamgabooceo`。当前版本已在 Dia 完成商店安装与基本界面检查；其他浏览器及离线安装是否允许，以浏览器实际提示为准，不保证所有 Chromium 浏览器兼容。

<details>
<summary>26.10.16.12 CRX 文件校验信息</summary>

文件：`hongyan-26.10.16.12.crx`，大小：4,131,681 字节。

SHA-256：`a458cc00e5d894e7fca41a6255eb58b6930882647e24768449f58c7b26fc18e2`

</details>

## 安装与更新

1. 优先使用浏览器允许的应用商店安装方式；页面可用时按提示添加红研。
2. 使用 CRX 时，打开浏览器的扩展程序管理页，将文件拖入并按提示添加，无需解压。浏览器禁止离线安装时改用商店，不关闭安全保护。
3. 启用后固定红研到工具栏，刷新已打开的平台页面，再核对版本与对应功能。

更新时保留原扩展和本机资料，不清除存储。同一商店 ID 的更新由浏览器处理；不同 ID 的安装不保证自动继承配置。不要同时启用两份红研。开发版与商店版不能仅凭名称判断为同一安装。

## 免费使用与源码

插件免费，无需激活，无试用期限。云端转录与内容解读需自行配置第三方服务并承担服务费用；新版本地 Whisper 不产生云端转录接口费用。

本公开仓库不包含扩展开发源码。GitHub 自动生成的 **Source code** 归档只有介绍仓库的文档和图片，不是插件安装包。

商业源码须[联系作者获得授权](https://extensions.zhangxun.org/hongyan/#wechat)，加入作者的 GitHub 私有仓库后获取；免费使用插件不包含商业源码授权。
