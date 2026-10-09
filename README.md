<!-- CYTECH_README_REFRESH:START -->
<div align="center">
<a href="https://github.com/CyoriaSMP-Team/CyoriaLauncher"><img width="100%" alt="CyoriaLauncher banner" src="https://capsule-render.vercel.app/api?type=waving&color=0:141026,100:8B5CF6&height=210&section=header&text=CyoriaLauncher&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=One%20workspace%20for%20desktop%20and%20mobile%20Minecraft%20launchers&descAlignY=59&descSize=16"></a>

<img alt="Project: Launcher Workspace" src="https://img.shields.io/badge/PROJECT-Launcher%20Workspace-8B5CF6?style=flat-square&labelColor=141026"> <img alt="Stack: Desktop · Android" src="https://img.shields.io/badge/STACK-Desktop%20%C2%B7%20Android-8B5CF6?style=flat-square&labelColor=141026">

<a href="https://github.com/CyoriaSMP-Team/CyoriaLauncher">Source</a> · <a href="https://github.com/CyoriaSMP-Team/CyoriaLauncher/issues">Issues</a> · <a href="https://github.com/CyoriaSMP-Team/CyoriaLauncher/releases">Releases</a>

</div>
<!-- CYTECH_README_REFRESH:END -->

---

Unified launcher workspace for **Desktop** and **Mobile**.

## Structure

- `desktop/` — desktop launcher application
- `mobile/` — Android/mobile launcher application
- `shared/` — shared sync schemas, protocol definitions, account metadata and cross-platform configuration

## Direction

CyoriaLauncher is the common home for both launcher clients so features such as account/session metadata, launcher settings, instance metadata and future cloud sync can share one versioned contract instead of drifting between separate repositories.

The two applications remain independently buildable. Cross-platform functionality should be introduced through `shared/` and explicit sync APIs rather than tightly coupling the desktop and mobile runtimes.

## Migration

This repository was created from current snapshots of the former launcher repositories. See [MIGRATION.md](MIGRATION.md) for source history and attribution.
