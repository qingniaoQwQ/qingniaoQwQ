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
      <p>我是 <b>QingNiaoQaQ</b>，<b>CatCraft</b> 创始人兼开发。主要开发在游戏服务端：写 Minecraft 插件、写 CS2 / CSGO 客户端插件、搭社区服务器，顺手把服务器官网和赛事页面也做了。</p>
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



<p align="center"><sub>QingNiaoQaQ · CatCraft Team</sub></p>
