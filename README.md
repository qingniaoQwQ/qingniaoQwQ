<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/logo-dark.png" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/logo-light.png" />
    <img src="./assets/logo-light.png" alt="CatCraft" height="150" />
  </picture>
</p>

<h1 align="center">QingNiaoQaQ</h1>

<h3 align="center">Java 全栈开发 · Minecraft 插件与服务器 · CS2 / CSGO 社区服务器</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Java-8%20~%2021-orange?logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Minecraft-Paper%20%7C%20Purpur%20%7C%20Folia-brightgreen?logo=spigotmc&logoColor=white" alt="Minecraft" />
  <img src="https://img.shields.io/badge/CS2%20%7C%20CSGO-Client%20Plugins-yellow?logo=counterstrike&logoColor=white" alt="CS2 / CSGO" />
  <img src="https://img.shields.io/badge/Database-MySQL%20%7C%20PostgreSQL%20%7C%20SQLite-blue?logo=postgresql&logoColor=white" alt="Database" />
  <img src="https://img.shields.io/badge/License-MIT-success" alt="License MIT" />
</p>

---

## 关于我

<table border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td width="176" align="center" valign="middle">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="./assets/avatar-card-dark.png" />
        <source media="(prefers-color-scheme: light)" srcset="./assets/avatar-card-light.png" />
        <img src="./assets/avatar-card-light.png" alt="QingNiaoQaQ" width="150" />
      </picture>
    </td>
    <td valign="middle">
      <p>我是 <b>QingNiao（QingNiaoQaQ）</b>，<b>CatCraft</b> 团队开发者。主战场在游戏服务端：写 Minecraft 插件、写 CS2 / CSGO 客户端插件、搭社区服务器，顺手把服务器官网和赛事页面也做了。</p>
      <ul>
        <li><img src="https://api.iconify.design/simple-icons:minecraft.svg?color=%2362b47a&height=16&width=16" height="16" alt="" /> 自研并运营 <b>CatCraft</b> Minecraft 生存服：插件、数据、官网整条链路都是自研</li>
        <li><img src="https://cdn.simpleicons.org/spigotmc/ED8106" height="16" alt="" /> Minecraft 插件：Java + Gradle，服务端适配 Spigot / Paper / Purpur / Folia</li>
        <li><img src="https://cdn.simpleicons.org/counterstrike/d29922" height="16" alt="" /> 自研并运营 <b>CatCraft</b> CS2 社区服；CS2 / CSGO 客户端插件开发（C++ / C# / SourcePawn）与服务端运维</li>
        <li><img src="https://api.iconify.design/octicon:globe.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> 顺带写 Web：服务器官网、数据站、赛事报名页等静态站点，GitHub Pages + Cloudflare 托管</li>
        <li><img src="https://api.iconify.design/octicon:book.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> 关心的东西：跨版本兼容、跨服数据同步、多数据库后端、国际化（中英双语）</li>
        <li><img src="https://api.iconify.design/octicon:mail.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> 联系方式在下方，优先 QQ 群、B 站私信或邮件</li>
      </ul>
    </td>
  </tr>
</table>

## 我在做什么

| 方向 | 内容 | 状态 |
| --- | --- | --- |
| <img src="https://api.iconify.design/simple-icons:minecraft.svg?color=%2362b47a&height=16&width=16" height="16" alt="" /> Minecraft 服务器 | **CatCraft** 生存服：玩法设计、插件自研、数据与运维 | 运营中 |
| <img src="https://cdn.simpleicons.org/spigotmc/ED8106" height="16" alt="" /> Minecraft 插件 | 服务端插件开发（Spigot / Paper / Purpur / Folia），代表作品 **CatCraftTitle** 头衔与后缀系统 | 持续维护 |
| <img src="https://cdn.simpleicons.org/counterstrike/d29922" height="16" alt="" /> CS2 / CSGO 社区服 | **CatCraft** CS2 社区服：客户端插件开发、服务端搭建与运维、赛事与对战配置（[服务器演示](https://www.bilibili.com/video/BV1dw836vEdg/)） | 进行中 |
| <img src="https://api.iconify.design/octicon:globe.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> Web 站点 | 服务器官网、数据站、赛事报名页等静态站点 | 维护中 |

## 代表项目

### CatCraftTitle — Minecraft 头衔与后缀管理插件

> 轻量级、支持 GUI 管理、中英双语、功能完善的 Minecraft 头衔与后缀管理插件。

- **多级头衔体系**：头衔与后缀分离，每个称号独立开关，玩家自助切换
- **图形化界面**：玩家端 `/catcraft gui`，管理端 `/titleadmin panel`（TPS / 在线 / 内存看板、按名或 UUID 搜索玩家）
- **多数据库后端**：MySQL / PostgreSQL / SQLite，连接失败时自动回退 SQLite，数据不丢
- **跨服同步**：基于 MySQL / PostgreSQL 实现多服务器共享玩家数据
- **自动称号**：基于表达式的条件判定（且 / 或 / 非、区间、字符串、正则），内置 30+ 变量，可脱离 PlaceholderAPI 运行
- **完整生态兼容**：PlaceholderAPI、Vault 经济、RGB 渐变、Tab / 头顶显示，Folia 上自动降级而非崩溃
- **工程化**：Gradle 构建，推送 tag 由 GitHub Actions 自动构建并发布 Release，MIT License

**技术栈**：`Java` `Spigot / Paper / Purpur / Folia API` `Gradle` `JDBC` `PlaceholderAPI` `Vault` `GitHub Actions`

<p>
  <img src="https://api.iconify.design/octicon:link-external.svg?color=%237d8590&height=16&width=16" height="16" alt="" />
  <a href="https://github.com/qingniaoQwQ/CatCraftTitle">github.com/qingniaoQwQ/CatCraftTitle</a>
</p>

其余仓库（服务器官网、赛事报名页、服务端页面等）见 <a href="https://github.com/qingniaoQwQ?tab=repositories">Repositories</a>。

## 技术栈

| 分类 | 具体 |
| --- | --- |
| <img src="https://api.iconify.design/octicon:code.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> 语言 | Java（8 ~ 21）、C#、C++、SourcePawn、HTML / CSS / JavaScript、SQL、Shell |
| <img src="https://cdn.simpleicons.org/spigotmc/ED8106" height="16" alt="" /> Minecraft 插件 | Spigot / Paper / Purpur / Folia API；PlaceholderAPI、Vault 等生态对接；Gradle 构建 |
| <img src="https://cdn.simpleicons.org/counterstrike/d29922" height="16" alt="" /> CS 客户端插件与赛事 | CS2：Metamod:Source（C++）、CounterStrikeSharp（C#）；CSGO：SourceMod（SourcePawn）；MatchZy / Get5 等比赛插件 |
| <img src="https://api.iconify.design/octicon:server.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> 服务端与部署 | SteamCMD、Docker、Linux；Minecraft 与 CS2 / CSGO 社区服务器搭建与日常运维 |
| <img src="https://api.iconify.design/octicon:database.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> 数据层 | MySQL、PostgreSQL、SQLite；连接回退与自动迁移、跨服数据同步 |
| <img src="https://api.iconify.design/octicon:package.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> 构建与发布 | Gradle（wrapper 9.3.0，兼容 JDK 24+）、GitHub Actions 自动构建 / Release |
| <img src="https://api.iconify.design/octicon:globe.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> 前端与托管 | 静态站点、GitHub Pages + CNAME 自定义域名、Cloudflare（DNS / Tunnel） |

## 找到我

| 平台 | 地址 |
| --- | --- |
| <img src="https://api.iconify.design/octicon:mark-github.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> GitHub | https://github.com/qingniaoQwQ |
| <img src="https://cdn.simpleicons.org/bilibili/00A1D6" height="16" alt="" /> B 站 | https://space.bilibili.com/1622211276 |
| <img src="https://api.iconify.design/octicon:globe.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> CatCraft 官网 | https://www.catcraft.online/ |
| <img src="https://api.iconify.design/octicon:graph.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> CatCraft 数据站 | https://rank.catcraft.online/ |
| <img src="https://cdn.simpleicons.org/qq/1EBAFC" height="16" alt="" /> QQ 群（CatCraft 社区） | `1097227114` |
| <img src="https://api.iconify.design/octicon:comment-discussion.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> MineBBS | https://www.minebbs.com/members/qingniaoqaq.338682/ |
| <img src="https://cdn.simpleicons.org/modrinth/00AF5C" height="16" alt="" /> Modrinth | https://modrinth.com/user/QingNiaoQaQ |
| <img src="https://api.iconify.design/octicon:link.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> NexusMC | https://www.nexusmc.cn/user/QingNiaoQaQ |
| <img src="https://api.iconify.design/octicon:mail.svg?color=%237d8590&height=16&width=16" height="16" alt="" /> 邮箱 | owner@catcraft.online |

---

## 主页更新记录

- **2026-09** 建立主页 README；接入 CatCraft 团队 Logo 与个人头像（深浅色双版本，随系统主题自动切换）；补充 CS2 / CSGO 方向

<!--
=====================================================================
维护须知
=====================================================================

【本 README 的设计原则：低维护成本】
写这个主页时特意避免了两类会过期的东西，新增插件/仓库时不需要回来改：
  1. 不逐个罗列仓库 —— 只在「代表项目」写旗舰作品 CatCraftTitle，其余用 Repositories 链接兜底；
     新开仓库不用动本文件。
  2. 不逐个罗列插件 —— CS 方向和 MC 方向都只描述「能力 + 技术栈 + 用到的东西」，
     新写一个插件只要没换技术体系，本文件依然准确。
  「主页更新记录」只在主页本身有实质性改动时才加一行。

【为什么圆角是烤进图片里的】
GitHub 会按白名单过滤 README 里的 HTML（源码见 github/html-pipeline 的 SanitizationFilter::WHITELIST）。
该白名单的属性列表里既没有 style 也没有 class，所以 border-radius / box-shadow 这类 CSS 一律会被剥掉。
因此圆角、描边、透明角全部在本地预处理时画进 PNG 的 Alpha 通道，GitHub 只负责显示，效果在任何客户端都一致。

【头像】assets/ 目录下四个变体，当前用的是 card 版：
  avatar-card-light.png    圆角卡片 + 浅灰描边 #d1d9e0  → 浅色模式显示
  avatar-card-dark.png     圆角卡片 + 中灰描边 #6e7681  → 深色模式显示
  avatar-round-light.png   正圆 + 浅灰描边              → 备用（想换成圆形头像就用它）
  avatar-round-dark.png    正圆 + 中灰描边              → 备用
  想从卡片换成正圆：把 README 里那两处 srcset 的文件名由 avatar-card-* 改成 avatar-round-* 即可。
  想删掉没用的变体：确认 README 没引用后直接删文件。
  源图 640x640 正方形 JPEG（无透明通道、底色接近纯白），已缩到 256x256；照片类内容存 PNG 偏大（约 115~127 KB/张），
  介意体积的话可降到 192x192。

【Logo】assets/logo-dark.png（浅色图形）与 assets/logo-light.png（深色图形），随主题切换。

【主题切换写法】用 <picture> + prefers-color-scheme，GitHub 官方文档明确写着 "The <picture> HTML element is supported."；
  旧的 #gh-dark-mode-only 片段写法已从官方文档移除，不要再用。

【卡片布局】"关于我" 用 HTML 表格 + valign/width 属性实现两栏（align / valign / width / border / cellpadding / cellspacing 都在白名单内）。
  注意：块级 HTML 标签内部 GitHub 不解析 Markdown，所以卡片里的加粗、列表必须写成 <b> / <ul> / <li>，写 ** 星号不会生效。

【图标】均为公开 CDN，GitHub 会通过 camo 代理缓存，读者侧网络不受影响：
  Simple Icons  https://cdn.simpleicons.org/<slug>/<十六进制色值>
  Iconify       https://api.iconify.design/<图标集>:<图标名>.svg?color=%23色值&height=16&width=16
  注意：Simple Icons 已下架 minecraft / tencentqq 等图标，所以 Minecraft 图标取自 Iconify 的 simple-icons 集；
        QQ 图标的 slug 是 qq，CS 图标的 slug 是 counterstrike（不是 counter-strike）。
        Octicons 里没有 people / trophy，需要「数据、统计」类图标用 octicon:graph，需要「在线」用 octicon:pulse。
  通用图标统一用 #7d8590（深浅色模式都能看清）；Counter-Strike 官方色是纯黑，深色模式下不可见，故改用琥珀色 #d29922。

【可选】第三方数据卡片（公共实例偶尔限流，国内访问不稳定，需要时再取消注释）

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=qingniaoQwQ&show_icons=true&theme=tokyonight&locale=cn" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=qingniaoQwQ&layout=compact&theme=tokyonight&locale=cn" height="165" />
</p>
-->

<p align="center"><sub>QingNiaoQaQ · CatCraft Team</sub></p>
