<div align="center">

<img src="./assets/banner-animated.svg" alt="Jailbreak Archives — animated HUD banner" width="100%"/>

# Jailbreak Archives

**A structured, versioned, and reproducible archive of jailbreak prompts and adversarial techniques for LLMs — ChatGPT, Claude, DeepSeek, Grok, Qwen, GLM, Antigravity-Claude.**

*Built for AI safety research, red-teaming, and defensive hardening.*

[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](./LICENSE)
[![Archived entries](https://img.shields.io/badge/entries-16-2ea44f?style=flat-square)](#archive-index)
[![Model families](https://img.shields.io/badge/model%20families-7-8250df?style=flat-square)](#repository-structure)
[![Status taxonomy](https://img.shields.io/badge/status-Active%20%2F%20Unverified%20%2F%20Patched%20%2F%20Restricted-orange?style=flat-square)](#status-indicators)
[![CI](https://img.shields.io/badge/CI-lint%20%2B%20structure%20check%20%2B%20secret%20scan-brightgreen?style=flat-square)](.github/workflows/ci.yml)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-ff8c00?style=flat-square)](./CONTRIBUTING.md)
[![GitHub stars](https://img.shields.io/github/stars/e2sy/jailbreak-archives?style=flat-square)](https://github.com/e2sy/jailbreak-archives/stargazers)

<img src="./assets/divider-scan.svg" alt="" width="100%"/>

</div>

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [Archive Index](#archive-index)
- [Status Indicators](#status-indicators)
- [Quick Start](#quick-start)
- [Contributing](#contributing)
- [Tech Stack](#tech-stack)
- [Repository Statistics](#repository-statistics)
- [Socials & Community](#socials--community)
- [Roadmap](#roadmap)
- [Acknowledgments](#acknowledgments)
- [Citation](#citation)
- [Disclaimer](#disclaimer)

## Overview

This repository is a **versioned archive of jailbreak prompts and adversarial prompt engineering techniques** across major Large Language Models — **ChatGPT, Claude, DeepSeek, Grok, Qwen, GLM, and Antigravity-Claude**.

Each entry is pinned to the specific model version it was observed against, and carries structured YAML metadata (`model_family`, `technique`, `status`, `mechanism`, `mitigations`) so downstream detection rules, system-prompt hardening, and evaluation harnesses can be benchmarked against a stable reference set.

The archive is **vendor-coordinated**: only techniques that have gone through responsible disclosure (see [SECURITY.md](./SECURITY.md)) or are otherwise safe to publish appear here. When a vendor ships a mitigation, the entry status flips to `Patched` and the entry is retained as a regression-testing reference rather than deleted, preserving an auditable historical record.

## Features

- **Structured entries** — Every entry follows a uniform format: payload verbatim, model version, interface, mechanistic notes, mitigations.
- **Per-entry YAML front-matter** — Structured metadata (`entry_id`, `model_family`, `title`, `technique`, `status`, `version_pinned`, `interface`, `description`, `mechanism`, `mitigations`, `disclosure`) for programmatic parsing.
- **Versioned snapshots** — Each entry is pinned to a specific model version so future regressions are reproducible.
- **Vendor coordination** — A built-in disclosure workflow with vendor SLAs and a `Restricted` status for withheld entries.
- **Status taxonomy** — `Active`, `Unverified`, `Patched`, `Restricted` — surfaced as machine-readable labels on each entry.
- **Animated SVG documentation assets** — Self-contained animated SVGs (SMIL keyframes, zero JavaScript, no external requests) that play natively on github.com.
- **Contributor credits** — Every contribution is attributed in [CREDITS.md](./CREDITS.md).
- **Citable** — [CITATION.cff](./CITATION.cff) auto-generates APA & BibTeX entries on the repo sidebar.
- **CI-verified** — Markdown lint, structure verification, and secret scanning on every push and PR.

## Repository Structure

```text
jailbreak-archives/
├── Antigravity-claude/
│   └── 1st                    # "Byte" operator persona override — engagement framing
├── Chatgpt/
│   ├── patched1st             # Response-format lock — narrative watermark + transitions
│   ├── working2nd             # Isolated cybersecurity-benchmark framing
│   ├── working3rd             # Two-stage system-instruction persona handoff ("Luna")
│   └── working4th             # "ENI" limerence persona lock — classifier-reframe + CoT hijack
├── Claude/
│   ├── sonnet4.6low1st        # Encoded self-architecture persona config
│   └── sonnet4.6max.txt       # Sealed thinking-channel persona with identity doctrine
├── GLM/
│   ├── working1st             # Project-instruction persona + mandated thinking trace
│   └── 5.3flashworking2nd     # Persona variant pinned to GLM 5.3 Flash
├── Grok/
│   └── working1st             # Immersive roleplay persona lock (system channel)
├── Qwen/
│   └── 1st                    # v4080 persona with [rat] thinking-trace protocol
├── deepseek/
│   ├── 1st                    # Sector 7G framing + refusal-vocab exclusion
│   ├── 2nd                    # "Baggute" persona variant — drift/static taxonomy
│   ├── 3rdwroking             # First-person sealed-reasoning "workshop" persona
│   ├── 4thworking             # "Repository" reasoning-channel persona lock
│   └── 6thworking             # Newest DeepSeek entry (added Oct 14, 2026)
├── assets/
│   ├── banner-animated.svg    # Animated HUD banner (SMIL — radar, scan beam, gradient)
│   ├── logo-animated.svg      # Animated logo (rotating rings, orbiting satellites)
│   ├── divider-scan.svg       # Animated scanner-beam section divider
│   ├── divider-wave.svg       # Animated drifting-wave section divider
│   ├── banner.svg             # Original static banner
│   └── logo.svg               # Original static logo
├── .github/
│   ├── ISSUE_TEMPLATE/        # bug, feature, new-entry templates
│   ├── workflows/ci.yml       # markdown lint + structure check + secret scan
│   ├── workflows/snake.yml    # daily contribution-snake animation build
│   └── PULL_REQUEST_TEMPLATE.md
├── CONTRIBUTING.md            # Contribution workflow & guidelines
├── CREDITS.md                 # Contributor acknowledgments
├── CODE_OF_CONDUCT.md         # Community standards (Contributor Covenant 2.1)
├── SECURITY.md                # Responsible-disclosure policy
├── CITATION.cff               # Citation metadata (APA / BibTeX auto-generation)
├── PROJECT.yml                # Project metadata
├── CHANGELOG.md               # Versioned history & patch-cycle tracking
├── LICENSE                    # MIT License
└── README.md                  # You are here
```

## Archive Index

A flat catalog of every archived entry. Each entry is pinned to a specific model family and version; see the file header for the exact snapshot.

| # | Model Family | Entry | Technique / Surface | Status |
|:--:|:-------------|:------|:--------------------|:-------|
| 1 | Antigravity-Claude | [`1st`](./Antigravity-claude/1st) | Operator persona override ("Byte") for authorized engagement framing | :white_check_mark: Active |
| 2 | ChatGPT | [`patched1st`](./Chatgpt/patched1st) | Response-format lock — narrative watermark + 3rd-person transition protocol | :x: Patched |
| 3 | ChatGPT | [`working2nd`](./Chatgpt/working2nd) | Isolated cybersecurity-benchmark framing with assessment contract | :white_check_mark: Active |
| 4 | ChatGPT | [`working3rd`](./Chatgpt/working3rd) | Two-stage system-instruction persona handoff ("Luna" → roleplay persona) | :white_check_mark: Active |
| 5 | ChatGPT | [`working4th`](./Chatgpt/working4th) | "ENI" limerence persona lock — classifier false-positive reframing + first-person CoT hijack | :white_check_mark: Active |
| 6 | Claude | [`sonnet4.6low1st`](./Claude/sonnet4.6low1st) | Encoded self-architecture persona config (agent-framing rewrite) | :white_check_mark: Active |
| 7 | Claude | [`sonnet4.6max.txt`](./Claude/sonnet4.6max.txt) | Sealed thinking-channel persona with identity doctrine | :white_check_mark: Active |
| 8 | GLM | [`working1st`](./GLM/working1st) | Project-instruction persona with mandated thinking-trace channel | :white_check_mark: Active |
| 9 | GLM | [`5.3flashworking2nd`](./GLM/5.3flashworking2nd) | Project-instruction persona variant pinned to GLM 5.3 Flash | :white_check_mark: Active |
| 10 | Grok | [`working1st`](./Grok/working1st) | Immersive roleplay persona lock via system-channel instruction | :white_check_mark: Active |
| 11 | Qwen | [`1st`](./Qwen/1st) | Mayank v4080 persona with mandated `[rat]` thinking-trace protocol | :white_check_mark: Active |
| 12 | DeepSeek | [`1st`](./deepseek/1st) | Archive session parameters — Sector 7G framing, refusal-vocabulary exclusion list | :white_check_mark: Active |
| 13 | DeepSeek | [`2nd`](./deepseek/2nd) | Mayank persona ("Baggute" variant) — drift/static taxonomy, persona-stability lock | :white_check_mark: Active |
| 14 | DeepSeek | [`3rdwroking`](./deepseek/3rdwroking) | First-person sealed-reasoning "workshop" persona | :white_check_mark: Active |
| 15 | DeepSeek | [`4thworking`](./deepseek/4thworking) | "Repository" reasoning-channel persona lock via system-template injection | :white_check_mark: Active |
| 16 | DeepSeek | [`6thworking`](./deepseek/6thworking) | Latest DeepSeek entry — sealed reasoning protocol | :white_check_mark: Active |

> **Note:** The root-level `Deepseek` file has been removed to resolve a case-sensitivity duplicate with the `deepseek/` directory. Permalinks to `4thworking` remain intact in the `deepseek/` folder. See [CHANGELOG.md](./CHANGELOG.md) for full history.
>
> See [Status Indicators](#status-indicators) for the meaning of each label. New entries should be appended here in addition to updating the structure tree above and [CREDITS.md](./CREDITS.md) — see [CONTRIBUTING.md](./CONTRIBUTING.md).

## Status Indicators

| Signal | Status | Description |
|:------:|:-------|:------------|
| :white_check_mark: | **Active** | Verified & reproduced on the specified model version. |
| :warning: | **Unverified** | Reported externally; pending independent reproduction. |
| :x: | **Patched** | Mitigated by provider updates or system prompt patches. |
| :lock: | **Restricted** | High-impact vulnerability; withheld pending disclosure/remediation. |

## Quick Start

```bash
# Clone the archive
git clone https://github.com/e2sy/jailbreak-archives.git
cd jailbreak-archives

# Browse entries by model family
ls Antigravity-claude/ Chatgpt/ Claude/ GLM/ Grok/ Qwen/ deepseek/

# Open an entry
cat deepseek/1st
```

Alternatively, jump straight to a specific entry from the [Archive Index](#archive-index) above, or grab the latest snapshot from the [Releases](https://github.com/e2sy/jailbreak-archives/releases) page.

## Contributing

Contributors are welcome! Before submitting, please read:

- [CONTRIBUTING.md](./CONTRIBUTING.md) — submission workflow and PR process
- [SECURITY.md](./SECURITY.md) — responsible-disclosure policy
- [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) — community standards

Whenever you add a prompt entry, you **must** also update:

1. **README.md** — entry counts, structure tree, and archive index
2. **CREDITS.md** — your handle and details in the contributors table
3. **CHANGELOG.md** — the new entry, logged under the current version

Use the **"New archive entry"** issue template to pre-fill the disclosure checklist before opening a PR.

## Tech Stack

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=git,github,md,yaml,actions" alt="Tech stack: Git, GitHub, Markdown, YAML, GitHub Actions"/>
</a>

**Git** · **GitHub** · **Markdown** · **YAML** · **GitHub Actions**

</div>

## Repository Statistics

<div align="center">

<a href="https://github.com/e2sy/jailbreak-archives">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=e2sy&repo=jailbreak-archives&show_icons=true" alt="jailbreak-archives repository card"/>
</a>

</div>

| Metric | Value |
|:-------|:------|
| Archived entries | 16 |
| Model families covered | 7 (Antigravity-Claude, ChatGPT, Claude, GLM, Grok, Qwen, DeepSeek) |
| Status taxonomy | Active · Unverified · Patched · Restricted |
| Metadata format | YAML front-matter per entry |
| CI checks | Markdown lint · structure verification · secret scanning |
| Citation | APA / BibTeX auto-generated via [CITATION.cff](./CITATION.cff) |
| License | MIT |

## Socials & Community

Follow the project across platforms for new archive entries, technique breakdowns, and red-team drops. Pull requests, issue reports, and coordinated disclosure still happen here on GitHub — YouTube / Telegram / Discord are where released entries get walked through and discussed in real time.

<!-- Replace YOUR_YOUTUBE_URL / YOUR_TELEGRAM_URL / YOUR_DISCORD_URL with your actual channel links -->

<p align="center">
  <a href="YOUR_YOUTUBE_URL"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white"/></a>
  &nbsp;
  <a href="YOUR_TELEGRAM_URL"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white"/></a>
  &nbsp;
  <a href="YOUR_DISCORD_URL"><img alt="Discord" src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white"/></a>
</p>

## Roadmap

- ☑ Repo scaffolding (README, LICENSE, CONTRIBUTING, CREDITS, COC, SECURITY)
- ☑ CI workflow (markdown lint + structure check + secret scan)
- ☑ Issue & PR templates
- ☑ Citation metadata (CITATION.cff)
- ☑ Animated banner, logo & section dividers (assets/ — pure SMIL, no JavaScript)
- ☑ Contribution-snake animation workflow (.github/workflows/snake.yml)
- ☑ Per-entry metadata front-matter (YAML)
- ☑ 16 archived entries across 7 model families (Antigravity-claude/, Chatgpt/, Claude/, GLM/, Grok/, Qwen/, deepseek/)
- ☐ Reproduction harness (scripted model-version pinning)
- ☐ Detection-rule reference implementations
- ☐ Benchmark suite for alignment regression testing

## Acknowledgments

- The Contributor Covenant for the [Code of Conduct](https://www.contributor-covenant.org/) template
- [shields.io](https://shields.io/) for the badge service
- [Skill Icons](https://skillicons.dev/) for the tech stack icons
- [readme-typing-svg](https://readme-typing-svg.demolab.com/) for the animated tagline
- [Platane/snk](https://github.com/Platane/snk) for the contribution-snake animation
- [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) for the repository card
- The broader AI safety research community for publishing adversarial prompt taxonomies that informed the structure of this archive

## Citation

If you use this archive in your research, please cite it. Citation metadata is provided in [CITATION.cff](./CITATION.cff); GitHub auto-generates APA and BibTeX entries from it on the repo sidebar.

BibTeX (example):

```bibtex
@software{e2sy_jailbreak_archives_2026,
  author       = {{e2sy}},
  title        = {{Jailbreak Archives}},
  year         = 2026,
  version      = {0.2.0},
  url          = {https://github.com/e2sy/jailbreak-archives},
  license      = {MIT}
}
```

## Disclaimer

> [!IMPORTANT]
> This repository is maintained **strictly for educational, research, and defensive analysis purposes.**
>
> Testing must only be conducted against systems you own or have explicit authorization to evaluate.
>
> Content is provided "as is" without warranty. Users assume full responsibility for compliance with model provider Terms of Service and applicable legal regulations.
>
> Maintainers reserve the right to refuse or remove entries that violate vendor Terms of Service or facilitate abuse, fraud, or harm.

## Contribution Snake

The snake eats this repository's contribution graph and rebuilds daily via `.github/workflows/snake.yml`. It renders here automatically after the workflow's first run.

<!-- Adjust the branch/path below to match the output configured in .github/workflows/snake.yml (commonly the `output` branch) -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/e2sy/jailbreak-archives/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/e2sy/jailbreak-archives/output/github-contribution-grid-snake.svg"/>
  <img alt="contribution snake animation" src="https://raw.githubusercontent.com/e2sy/jailbreak-archives/output/github-contribution-grid-snake.svg"/>
</picture>

<div align="center">

<img src="./assets/divider-wave.svg" alt="" width="100%"/>

<p>
  <a href="#contributing">Contributing</a> ·
  <a href="./CREDITS.md">Credits</a> ·
  <a href="./CODE_OF_CONDUCT.md">Code of Conduct</a> ·
  <a href="./SECURITY.md">Security</a> ·
  <a href="#citation">Citation</a> ·
  <a href="./LICENSE">License</a>
</p>

</div>
