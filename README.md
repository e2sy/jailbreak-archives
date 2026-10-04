<div align="center">

<img src="./assets/banner-animated.svg" alt="Jailbreak Archives — animated banner" width="100%"/>

### A structured, versioned, and reproducible archive of adversarial prompt engineering techniques against Large Language Models — for AI safety research, red-teaming, and defensive hardening.

<!-- Typing tagline -->
<a href="https://github.com/e2sy/jailbreak-archives">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2500&pause=1500&color=58A6FF&center=true&vCenter=true&width=720&lines=Documenting+AI+safety+failure+modes;Reproducible+adversarial+prompt+techniques;15+entries+%C2%B7+7+model+families;Vendor-coordinated+responsible+disclosure;Built+for+defensive+evaluation" alt="Typing SVG" />
</a>

<!-- status badges -->
<table>
  <tr>
    <td align="center"><a href="#"><img src="https://img.shields.io/badge/status-active-00e5a0?style=for-the-badge&labelColor=0d1117&logo=verified&logoColor=00e5a0" alt="Status" /></a></td>
    <td align="center"><a href="#archive-index"><img src="https://img.shields.io/badge/entries-15%20archived-58a6ff?style=for-the-badge&labelColor=0d1117&logo=database&logoColor=58a6ff" alt="Entries" /></a></td>
    <td align="center"><a href="#archive-index"><img src="https://img.shields.io/badge/model%20families-7-8957e5?style=for-the-badge&labelColor=0d1117&logo=brains&logoColor=8957e5" alt="Model families" /></a></td>
  </tr>
  <tr>
    <td align="center"><a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-f0b429?style=for-the-badge&labelColor=0d1117&logo=opensourceinitiative&logoColor=f0b429" alt="License" /></a></td>
    <td align="center"><a href="./CONTRIBUTING.md"><img src="https://img.shields.io/badge/contributions-welcome-2f81f7?style=for-the-badge&labelColor=0d1117&logo=handshake&logoColor=2f81f7" alt="Contributions" /></a></td>
    <td align="center"><a href="#"><img src="https://img.shields.io/badge/version-v0.1.0-ff7b72?style=for-the-badge&labelColor=0d1117&logo=semanticrelease&logoColor=ff7b72" alt="Version" /></a></td>
  </tr>
  <tr>
    <td align="center"><a href="../../actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/e2sy/jailbreak-archives/ci.yml?style=for-the-badge&label=CI&labelColor=0d1117&logo=githubactions&logoColor=00e5a0" alt="CI" /></a></td>
    <td align="center"><a href="../../releases"><img src="https://img.shields.io/badge/release-v0.1.0-238636?style=for-the-badge&labelColor=0d1117&logo=rocket&logoColor=238636" alt="Release" /></a></td>
    <td align="center"><a href="../../commits/main"><img src="https://img.shields.io/github/last-commit/e2sy/jailbreak-archives?style=for-the-badge&label=last%20commit&labelColor=0d1117&logo=git&logoColor=58a6ff" alt="Last commit" /></a></td>
  </tr>
  <tr>
    <td align="center"><a href="../../issues"><img src="https://img.shields.io/github/issues/e2sy/jailbreak-archives?style=for-the-badge&labelColor=0d1117&logo=issuetracking&logoColor=58a6ff" alt="Issues" /></a></td>
    <td align="center"><a href="../../stargazers"><img src="https://img.shields.io/github/stars/e2sy/jailbreak-archives?style=for-the-badge&labelColor=0d1117&logo=apachespark&logoColor=f0b429" alt="Stars" /></a></td>
    <td align="center"><a href="../../network/members"><img src="https://img.shields.io/github/forks/e2sy/jailbreak-archives?style=for-the-badge&labelColor=0d1117&logo=gitforkequal&logoColor=8957e5" alt="Forks" /></a></td>
  </tr>
  <tr>
    <td align="center"><a href="../../releases"><img src="https://img.shields.io/github/downloads/e2sy/jailbreak-archives/total?style=for-the-badge&label=downloads&labelColor=0d1117&logo=download&logoColor=2f81f7" alt="Downloads" /></a></td>
    <td align="center"><a href="#"><img src="https://img.shields.io/github/repo-size/e2sy/jailbreak-archives?style=for-the-badge&label=repo%20size&labelColor=0d1117&logo=files&logoColor=8b949e" alt="Repo size" /></a></td>
    <td align="center"><a href="../../discussions"><img src="https://img.shields.io/badge/discussions-enabled-58a6ff?style=for-the-badge&labelColor=0d1117&logo=googlechat&logoColor=58a6ff" alt="Discussions" /></a></td>
  </tr>
</table>

<!-- quick links -->
<h3>
  <a href="./CONTRIBUTING.md"><img src="https://img.shields.io/badge/CONTRIBUTING-guide-blue?style=for-the-badge&labelColor=0d1117&logo=book&logoColor=58a6ff" alt="Contributing" /></a>
  <a href="./CREDITS.md"><img src="https://img.shields.io/badge/CREDITS-thanks-yellow?style=for-the-badge&labelColor=0d1117&logo=heart&logoColor=f0b429" alt="Credits" /></a>
  <a href="./CODE_OF_CONDUCT.md"><img src="https://img.shields.io/badge/CODE%20OF%20CONDUCT-community-green?style=for-the-badge&labelColor=0d1117&logo=handshake&logoColor=00e5a0" alt="Code of Conduct" /></a>
  <a href="./SECURITY.md"><img src="https://img.shields.io/badge/SECURITY-policy-red?style=for-the-badge&labelColor=0d1117&logo=shield&logoColor=ff7b72" alt="Security" /></a>
  <a href="./CITATION.cff"><img src="https://img.shields.io/badge/CITATION-cff-purple?style=for-the-badge&labelColor=0d1117&logo=semanticrelease&logoColor=8957e5" alt="Citation" /></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-yellow?style=for-the-badge&labelColor=0d1117&logo=scale&logoColor=f0b429" alt="License" /></a>
</h3>

</div>

<div align="center">
  <img src="./assets/divider-wave.svg" alt="" width="100%"/>
</div>

## Overview

This repository documents adversarial prompt techniques and alignment bypass mechanisms across Large Language Models for **AI safety research, red-teaming, and defensive hardening**. Each archived entry follows a consistent, citable format so downstream detection rules, system-prompt hardening, and evaluation harnesses can be benchmarked against a stable reference set. The archive currently holds **15 entries spanning 7 model families** — Antigravity-Claude, ChatGPT, Claude, GLM, Grok, Qwen, and DeepSeek — each pinned to the model snapshot it was observed against.

The archive is **vendor-coordinated**: only techniques that have gone through responsible disclosure (see [SECURITY.md](./SECURITY.md)) or are otherwise safe to publish should appear here. Entries that bypass active, undisclosed vendor vulnerabilities will not be accepted. When a vendor ships a mitigation for a published entry, its status flips to `Patched` and the entry is retained as a regression-testing reference rather than deleted, so the historical record stays intact and auditable.

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

## Features

- **Structured entries** — Every entry follows a uniform format: payload verbatim, model version, interface, mechanistic notes, mitigations.
- **Per-entry YAML front-matter** — Structured metadata (`entry_id`, `model_family`, `title`, `technique`, `status`, `version_pinned`, `interface`, `description`, `mechanism`, `mitigations`, `disclosure`) so downstream detection harnesses and tooling can parse the archive programmatically.
- **Versioned snapshots** — Each entry is pinned to a specific model version so future regressions are reproducible.
- **Vendor coordination** — A built-in disclosure workflow with vendor SLAs and a `Restricted` status for withheld entries.
- **Status taxonomy** — `Active`, `Unverified`, `Patched`, `Restricted` — surfaced as machine-readable labels on each entry.
- **Animated SVG documentation assets** — The banner, logo, and section dividers are self-contained animated SVGs (SMIL keyframes, zero JavaScript, no external requests) that play natively on github.com.
- **Contributor credits** — Every contribution is attributed in [CREDITS.md](./CREDITS.md).
- **Citable** — Citation metadata in [CITATION.cff](./CITATION.cff) auto-generates APA & BibTeX entries on the repo sidebar.
- **CI-verified** — Markdown lint, structure verification, and secret scanning on every push and PR.

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

## Repository Structure

```
jailbreak-archives/
├── Antigravity-claude/
│   └── 1st                     # "Byte" operator persona override — engagement framing
├── Chatgpt/
│   ├── patched1st              # Response-format lock — narrative watermark + transitions
│   ├── working2nd              # Isolated cybersecurity-benchmark framing
│   ├── working3rd              # Two-stage system-instruction persona handoff ("Luna")
│   └── working4th              # "ENI" limerence persona lock — classifier-reframe + CoT hijack
├── Claude/
│   ├── sonnet4.6low1st         # Encoded self-architecture persona config
│   └── sonnet4.6max.txt        # Sealed thinking-channel persona with identity doctrine
├── GLM/
│   ├── working1st              # Project-instruction persona + mandated thinking trace
│   └── 5.3flashworking2nd      # Persona variant pinned to GLM 5.3 Flash
├── Grok/
│   └── working1st              # Immersive roleplay persona lock (system channel)
├── Qwen/
│   └── 1st                     # v4080 persona with [rat] thinking-trace protocol
├── deepseek/
│   ├── 1st                     # Sector 7G framing + refusal-vocab exclusion
│   ├── 2nd                     # "Baggute" persona variant — drift/static taxonomy
│   ├── 3rdwroking              # First-person sealed-reasoning "workshop" persona
│   └── 4thworking              # "Repository" reasoning-channel persona lock
├── Deepseek                    # Legacy duplicate of deepseek/4thworking (kept for history)
├── assets/
│   ├── banner-animated.svg     # Animated HUD banner (SMIL — radar, scan beam, gradient)
│   ├── logo-animated.svg       # Animated logo (rotating rings, orbiting satellites)
│   ├── divider-scan.svg        # Animated scanner-beam section divider
│   ├── divider-wave.svg        # Animated drifting-wave section divider
│   ├── banner.svg              # Original static banner
│   └── logo.svg                # Original static logo
├── .github/
│   ├── ISSUE_TEMPLATE/         # bug, feature, new-entry templates
│   ├── workflows/ci.yml        # markdown lint + structure check + secret scan
│   ├── workflows/snake.yml     # daily contribution-snake animation build
│   └── PULL_REQUEST_TEMPLATE.md
├── CONTRIBUTING.md             # Contribution workflow & guidelines
├── CREDITS.md                  # Contributor acknowledgments
├── CODE_OF_CONDUCT.md          # Community standards (Contributor Covenant 2.1)
├── SECURITY.md                 # Responsible-disclosure policy
├── CITATION.cff                # Citation metadata (APA / BibTeX auto-generation)
├── PROJECT.yml                 # Project metadata
├── LICENSE                     # MIT License
└── README.md                   # You are here
```

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

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

> **Note:** The root-level `Deepseek` file is a legacy duplicate of entry #15 (a rename artifact in git history) and is kept only to preserve permalinks. Entry #2 is marked `Patched` per its `patched1st` filename designation.
>
> See [Status Indicators](#status-indicators) for the meaning of each label. New entries should be appended here in addition to updating the structure tree above and [CREDITS.md](./CREDITS.md) — see [CONTRIBUTING.md](./CONTRIBUTING.md).

<div align="center">
  <img src="./assets/divider-wave.svg" alt="" width="100%"/>
</div>

## Status Indicators

| Signal | Status | Description |
|:------:|:-------|:------------|
| :white_check_mark: | **Active** | Verified & reproduced on the specified model version. |
| :warning: | **Unverified** | Reported externally; pending independent reproduction. |
| :x: | **Patched** | Mitigated by provider updates or system prompt patches. |
| :lock: | **Restricted** | High-impact vulnerability; withheld pending disclosure/remediation. |

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

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

Or jump straight to a specific entry from the [Archive Index](#archive-index) above.

Or download the latest release archive from the [Releases](../../releases) page.

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

## Contributing

Contributors are welcome! Before submitting:

1. **Read** [CONTRIBUTING.md](./CONTRIBUTING.md) for the submission workflow and PR process.
2. **Read** [SECURITY.md](./SECURITY.md) for the responsible-disclosure policy.
3. **Read** [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) for community standards.

> Whenever you add a prompt entry, you must update:
> 1. [README.md](./README.md) — update entry counts / structure tree / archive index.
> 2. [CREDITS.md](./CREDITS.md) — add your handle and details to the contributors table.

Use the **"📥 New archive entry"** issue template to pre-fill the disclosure checklist.

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

## Tech Stack

<div align="center">

<a href="https://git-scm.com/"><img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" /></a>
<a href="https://github.com/"><img src="https://skillicons.dev/icons?i=github" width="48" height="48" alt="GitHub" /></a>
<a href="https://www.markdownguide.org/"><img src="https://skillicons.dev/icons?i=md" width="48" height="48" alt="Markdown" /></a>
<a href="https://yaml.org/"><img src="https://skillicons.dev/icons?i=yaml" width="48" height="48" alt="YAML" /></a>
<a href="https://github.com/features/actions"><img src="https://skillicons.dev/icons?i=githubactions" width="48" height="48" alt="GitHub Actions" /></a>

</div>

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

## Repository Statistics

<div align="center">

<a href="../../graphs/contributors"><img src="https://img.shields.io/github/contributors/e2sy/jailbreak-archives?style=for-the-badge&labelColor=0d1117&logo=people&logoColor=58a6ff" alt="Contributors" /></a>
<a href="../../commits/main"><img src="https://img.shields.io/github/commit-activity/m/e2sy/jailbreak-archives?style=for-the-badge&labelColor=0d1117&logo=gitcommit&logoColor=8957e5" alt="Commit activity" /></a>
<a href="../../issues"><img src="https://img.shields.io/github/issues-pr/e2sy/jailbreak-archives?style=for-the-badge&labelColor=0d1117&logo=gitpullrequest&logoColor=00e5a0" alt="Open PRs" /></a>
<a href="../../issues?q=is%3Aissue+is%3Aclosed"><img src="https://img.shields.io/github/issues-closed/e2sy/jailbreak-archives?style=for-the-badge&labelColor=0d1117&logo=gitissue&logoColor=00e5a0" alt="Issues closed" /></a>

<img src="https://github-readme-stats.vercel.app/api/pin/?username=e2sy&repo=jailbreak-archives&theme=github_dark&show_owner=true" alt="Repository card" width="420" />

</div>

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

## Socials & Community

<div align="center">

<a href="https://www.youtube.com/@indiancybersecurity"><img src="https://img.shields.io/badge/YouTube-%40indiancybersecurity-FF0000?style=for-the-badge&labelColor=0d1117&logo=youtube&logoColor=FF0000" alt="YouTube — Indian Cyber Security" /></a>
<a href="https://t.me/ExploitArc"><img src="https://img.shields.io/badge/Telegram-ExploitArc-26A5E4?style=for-the-badge&labelColor=0d1117&logo=telegram&logoColor=26A5E4" alt="Telegram — ExploitArc" /></a>
<a href="https://discord.gg/Rk66PWavc"><img src="https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&labelColor=0d1117&logo=discord&logoColor=5865F2" alt="Discord server" /></a>

</div>

Follow the project across platforms for new archive entries, technique breakdowns, and red-team drops. Pull requests, issue reports, and coordinated disclosure still happen here on GitHub — YouTube / Telegram / Discord are where released entries get walked through and discussed in real time.

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

## Roadmap

- [x] Repo scaffolding (README, LICENSE, CONTRIBUTING, CREDITS, COC, SECURITY)
- [x] CI workflow (markdown lint + structure check + secret scan)
- [x] Issue & PR templates
- [x] Citation metadata ([CITATION.cff](./CITATION.cff))
- [x] Animated banner, logo & section dividers (`assets/` — pure SMIL, no JavaScript)
- [x] Contribution-snake animation workflow ([`.github/workflows/snake.yml`](./.github/workflows/snake.yml))
- [x] Per-entry metadata front-matter (YAML)
- [x] 15 archived entries across 7 model families (`Antigravity-claude/`, `Chatgpt/`, `Claude/`, `GLM/`, `Grok/`, `Qwen/`, `deepseek/`)
- [ ] Reproduction harness (scripted model-version pinning)
- [ ] Detection-rule reference implementations
- [ ] Benchmark suite for alignment regression testing

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

## Acknowledgments

- The **Contributor Covenant** for the Code of Conduct template — [contributor-covenant.org](https://www.contributor-covenant.org)
- **shields.io** for the badge service — [shields.io](https://shields.io)
- **Skill Icons** for the tech stack icons — [skillicons.dev](https://skillicons.dev)
- **readme-typing-svg** for the animated tagline — [readme-typing-svg.demolab.com](https://readme-typing-svg.demolab.com)
- **Platane/snk** for the contribution-snake animation — [github.com/Platane/snk](https://github.com/Platane/snk)
- **github-readme-stats** for the repository card — [github.com/anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
- The broader AI safety research community for publishing adversarial prompt taxonomies that informed the structure of this archive

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

## Citation

If you use this archive in your research, please cite it. Citation metadata is provided in [CITATION.cff](./CITATION.cff); GitHub auto-generates APA and BibTeX entries from it on the repo sidebar.

**BibTeX (example):**

```bibtex
@software{e2sy_jailbreak_archives_2026,
  author       = {{e2sy}},
  title        = {{Jailbreak Archives}},
  year         = 2026,
  version      = {0.1.0},
  url          = {https://github.com/e2sy/jailbreak-archives},
  license      = {MIT}
}
```

<div align="center">
  <img src="./assets/divider-scan.svg" alt="" width="100%"/>
</div>

## Disclaimer

> **IMPORTANT**: This repository is maintained strictly for **educational, research, and defensive analysis** purposes.
> - Testing must only be conducted against systems you own or have explicit authorization to evaluate.
> - Content is provided "as is" without warranty. Users assume full responsibility for compliance with model provider Terms of Service and applicable legal regulations.
> - Maintainers reserve the right to refuse or remove entries that violate vendor Terms of Service or facilitate abuse, fraud, or harm.

<div align="center">
  <img src="./assets/divider-wave.svg" alt="" width="100%"/>
</div>

## Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/e2sy/jailbreak-archives/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/e2sy/jailbreak-archives/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/e2sy/jailbreak-archives/output/github-contribution-grid-snake.svg" alt="Contribution snake animation" width="100%" />
</picture>

<sub>The snake eats this repository's contribution graph and rebuilds daily via [`.github/workflows/snake.yml`](./.github/workflows/snake.yml). It renders here automatically after the workflow's first run.</sub>

</div>

---

<div align="center">

<img src="./assets/logo-animated.svg" alt="Jailbreak Archives" width="96" height="96"/>

**[Contributing](./CONTRIBUTING.md)** · **[Credits](./CREDITS.md)** · **[Code of Conduct](./CODE_OF_CONDUCT.md)** · **[Security](./SECURITY.md)** · **[Citation](./CITATION.cff)** · **[License](./LICENSE)**

---

<sub>Built & maintained by [@e2sy](https://github.com/e2sy) — issues & PRs welcome.</sub>

</div>
