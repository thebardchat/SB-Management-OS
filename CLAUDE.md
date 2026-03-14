# CLAUDE.md — SB-Management-OS

> Claude Code configuration for the `thebardchat/SB-Management-OS` repository.

---

## Project Overview

This repository is the **Small Business Management Operating System** — a lightweight, web-based operations toolkit for a ready-mix concrete company in North Alabama. It includes SOPs, coaching scripts, performance audits, and daily affirmations.

This project operates under the [ShaneTheBrain Constitution](https://github.com/thebardchat/constitution/blob/main/CONSTITUTION.md).

---

## Infrastructure

All `thebardchat` repositories run on the following local-first infrastructure:

| Component | Detail |
|-----------|--------|
| **Compute** | Raspberry Pi 5 (16 GB RAM) |
| **Chassis** | Pironman 5-MAX by Sunfounder (NVMe RAID) |
| **Storage** | 2x WD Blue SN5000 2 TB NVMe — RAID 1 via mdadm |
| **Core path** | `/mnt/shanebrain-raid/shanebrain-core/` |
| **Networking** | Tailscale VPN across all nodes |
| **Dev environment** | Claude Code on Pi 5 |

> Pi before cloud. Privacy before convenience. — Pillar 4

---

## Repository Structure

```
SB-Management-OS/
  index.html                        # Main landing page
  styles.css                        # Stylesheet
  README.md                         # Public-facing summary
  CLAUDE.md                         # This file — Claude Code project context
  SOPs/
    cleanliness-standards.html      # Cleanliness SOP
    service-efficiency.html         # Service efficiency SOP
  affirmations/
    morning-fire.html               # Morning motivational content
  personnel/
    performance-audit.html          # Performance audit tool
  scripts/
    game-plan-interview.html        # Interview game plan
    grow-coaching.html              # GROW coaching model guide
```

---

## Working With This Repo

- This is a static HTML/CSS project — no build step required.
- Open `index.html` in a browser or serve with any static file server.
- Follow the Constitution's amendment process for structural changes.
- Reference the Constitution — never copy it:
  ```md
  This project operates under the [ShaneTheBrain Constitution](https://github.com/thebardchat/constitution/blob/main/CONSTITUTION.md).
  ```

---

## Credits

Built with Claude (Anthropic) · Runs on Raspberry Pi 5 + Pironman 5-MAX

| Partner | Role |
|---------|------|
| **Claude by Anthropic** · [claude.ai](https://claude.ai) | Co-built this entire ecosystem |
| **Raspberry Pi 5** · [raspberrypi.com](https://www.raspberrypi.com) | Local compute backbone |
| **Pironman 5-MAX** · [pironman.com](https://www.pironman.com) | NVMe RAID 1 chassis that made it real |

---

*[@thebardchat](https://github.com/thebardchat) · Hazel Green, Alabama*

## Claude Code Rules
- Commit and push directly to `main`. Do NOT create branches.
- Run build/test commands before committing.
- Update CLAUDE.md session log before final commit.
