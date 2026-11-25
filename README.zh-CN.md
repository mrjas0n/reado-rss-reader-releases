<p align="center">
  <img src="https://reado.geoye.com/assets/reado-icon.png" width="96" alt="瑞读 reado 图标" />
</p>

<h1 align="center">瑞读 reado</h1>

<p align="center"><a href="README.md">English</a> · 简体中文</p>

<p align="center"><strong>把新闻读明白</strong><br />聚合你主动订阅的新闻源，用 AI 提炼每日重点，并保留每一条原始来源。</p>

<p align="center">
  <a href="https://github.com/mrjas0n/reado-rss-reader-releases/releases/latest/download/reado-setup.exe"><strong>下载 Windows 客户端</strong></a>
  ·
  <a href="https://github.com/mrjas0n/reado-rss-reader-releases/releases/latest">版本记录</a>
  ·
  <a href="https://reado.geoye.com">官网</a>
</p>

<p align="center"><sub>Windows 10/11 · x64 · NSIS 安装版 · 基于 GitHub Releases 的签名自动更新</sub></p>

---

## 少一点刷屏，多一点判断

瑞读只为你主动订阅的新闻源服务，不靠推荐流制造停留。

- **多源新闻聚合**：导入 OPML，或从 2000+ 推荐源里挑选；订阅、分类、搜索都在本地完成。
- **AI 新闻摘要**：用你自己配置的模型生成每日新闻摘要，或直接问「今天有什么大事」。
- **每条都有来源**：摘要带 `[n]` 引用，点击即可回到原始新闻；只基于你的订阅，不编造外部信息。
- **跨设备同步**：登录后同步订阅、分类与已读/星标状态；只同步这些元数据，新闻正文不上传。
- **本地优先**：数据默认保存在本机 SQLite；启动时与运行期间按设置间隔自动备份（最多保留 6 份），也可随时手动备份/恢复。
- **桌面体验**：三栏阅读界面、全文搜索、Reader 正文抽取、隐藏源、多种主题、系统托盘常驻、系统代理/直连。

## 下载

Windows 安装版：

- 最新版直链：[reado-setup.exe](https://github.com/mrjas0n/reado-rss-reader-releases/releases/latest/download/reado-setup.exe)
- 历史版本与校验信息：[Releases](https://github.com/mrjas0n/reado-rss-reader-releases/releases)

安装后应用会自动检查并提示新版本，无需逐版升级——每次更新都会直接获取最新安装包。

## 数据与隐私

| 项目 | 位置 |
| --- | --- |
| 订阅 / 文章数据库 | `%APPDATA%\com.rssreader.app\rss-reader.db`（仅本机） |
| 自动与手动备份 | `%APPDATA%\com.rssreader.app\backups\`（默认最多 6 份） |
| AI Token | Windows 凭据管理器（仅本机安全存储，不上传） |
| 同步账号 | 仅同步订阅、分类、已读/星标等元数据；文章正文与 Token 不同步 |

- 注册同步账号需要邀请码，一码一注册。
- 登录一次后可离线查看已缓存新闻；游客模式下数据只在本机。
- 新闻内容与版权归原作者及来源站点所有，瑞读只做订阅聚合与阅读。

## 关于本仓库

本仓库承载瑞读桌面端的发布产物：安装包、更新签名（`.sig`）与 `latest.json` 更新清单。应用通过上述直链或 [reado.geoye.com](https://reado.geoye.com) 下载与更新。

---

<sub>READO · RSS READER — A news aggregator you control. · <a href="README.md">English</a></sub>
