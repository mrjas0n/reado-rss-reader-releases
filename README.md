<p align="center">
  <img src="https://reado.geoye.com/assets/reado-icon.png" width="96" alt="Reado app icon" />
</p>

<h1 align="center">Reado</h1>

<p align="center"><strong>Read the news clearly</strong><br />Aggregate the sources you choose, let AI distill the day's key stories, and keep every original source.</p>

<p align="center">
  <a href="https://github.com/mrjas0n/reado-rss-reader-releases/releases/latest/download/reado-setup.exe"><strong>Download for Windows</strong></a>
  ·
  <a href="https://github.com/mrjas0n/reado-rss-reader-releases/releases/latest">Release notes</a>
  ·
  <a href="https://reado.geoye.com">Website</a>
  ·
  <a href="README.zh-CN.md">简体中文</a>
</p>

<p align="center"><sub>Windows 10/11 · x64 · NSIS installer · Signed auto-updates via GitHub Releases</sub></p>

---

## Less scrolling, more judgment

Reado serves only the sources you subscribe to. No recommendation feed engineered to keep you scrolling.

- **Multi-source aggregation**: Import OPML or pick from 2,000+ recommended feeds; subscriptions, categories and search all stay local.
- **AI news summaries**: Use your own model for a daily digest, or ask "What happened today?"
- **Every claim has a source**: Summaries include `[n]` citations that link back to the original story; grounded only in your subscriptions, with no invented facts.
- **Cross-device sync**: Sign in to sync subscriptions, categories, and read/starred state; only this metadata syncs — article text is never uploaded.
- **Local-first**: Data lives in local SQLite by default; automatic backups run at your chosen interval (up to 6 kept), with manual backup and restore available at any time.
- **Desktop experience**: Three-column reading, full-text search, Reader extraction, hidden feeds, multiple themes, system tray, system proxy/direct connection.

## Download

Windows installer:

- Latest direct link: [reado-setup.exe](https://github.com/mrjas0n/reado-rss-reader-releases/releases/latest/download/reado-setup.exe)
- Older versions and checksums: [Releases](https://github.com/mrjas0n/reado-rss-reader-releases/releases)

After installation, the app checks for updates automatically and always fetches the latest installer — there is no need to upgrade version by version.

## Data & privacy

| Item | Location |
| --- | --- |
| Subscription / article database | `%APPDATA%\com.rssreader.app\rss-reader.db` (local only) |
| Automatic and manual backups | `%APPDATA%\com.rssreader.app\backups\` (up to 6 by default) |
| AI tokens | Windows Credential Manager (secure local storage; never uploaded) |
| Sync account | Syncs only subscriptions, categories, read/starred metadata; article text and tokens are not synced |

- A sync account requires an invite code — one code per registration.
- Sign in once, then read cached news offline; guest mode keeps all data on this device.
- News content and copyright belong to the original authors and source sites; Reado only aggregates subscriptions for reading.

## About this repository

This repository hosts Reado's desktop release artifacts: installers, update signatures (`.sig`) and the `latest.json` update manifest. The app downloads and updates via the links above or [reado.geoye.com](https://reado.geoye.com).

---

<sub>READO · RSS READER — A news aggregator you control. · <a href="README.zh-CN.md">简体中文</a></sub>
