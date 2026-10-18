# QingYuan Li

I build and contribute to practical developer tools, self-hosted infrastructure, and AI-adjacent workflows.

## Selected contributions

### [Downvid](https://github.com/Downvid/downvid)

A modern cross-platform video downloader built around yt-dlp and FFmpeg.

**Contribution:** [Docker support and native WebUI integration · PR #70](https://github.com/Downvid/downvid/pull/70)

- Added a container deployment path without changing the desktop core
- Reused the existing WebUI through a thin compatibility bridge
- Added WebSocket RPC support and container-specific service boundaries
- Kept the container surface safer with localhost defaults and Origin checks

[![Stars](https://img.shields.io/github/stars/Downvid/downvid?style=flat-square)](https://github.com/Downvid/downvid)
[![Forks](https://img.shields.io/github/forks/Downvid/downvid?style=flat-square)](https://github.com/Downvid/downvid)

### [Data Maskit](https://github.com/xiaYuTian11/maskit)

A local privacy gateway that masks sensitive data before sending requests to AI services and restores streaming responses locally.

**Contribution:** [CSP and update-check reliability · PR #32](https://github.com/xiaYuTian11/maskit/pull/32)

- Fixed browser CSP blocking the GitHub update check
- Added a server-side fallback and neutral error handling
- Added regression coverage for the browser and backend paths

[![Stars](https://img.shields.io/github/stars/xiaYuTian11/maskit?style=flat-square)](https://github.com/xiaYuTian11/maskit)
[![Forks](https://img.shields.io/github/forks/xiaYuTian11/maskit?style=flat-square)](https://github.com/xiaYuTian11/maskit)

## Current work

### [WorkBuddy Manager](https://github.com/ithtelab/workbuddy-manager)

Working on a GitHub mirror update path for deployments where direct GitHub access is unreliable.

- Optional mirror support for API metadata and release assets
- Direct-connection fallback when a mirror is unavailable
- SHA-256 verification for downloaded release packages
- Windows, Docker, and native deployment coverage

**Open contribution:** [Add GitHub mirror update support · PR #218](https://github.com/ithtelab/workbuddy-manager/pull/218)

## Focus

- Developer tooling and automation
- Self-hosted deployment workflows
- AI gateways and privacy-aware infrastructure
- Small, testable changes that improve reliability in real deployments

## Toolbox

`Python` · `TypeScript` · `React` · `Next.js` · `FastAPI` · `Docker` · `PowerShell` · `GitHub Actions`

## More

- [Repositories](https://github.com/Glaroday?tab=repositories)
- [Contributions](https://github.com/Glaroday?tab=overview)
