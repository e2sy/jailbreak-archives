<div align="center">

<img src="./assets/banner.svg" alt="Jailbreak Archive" width="100%"/>

### A structured, versioned, and reproducible archive of adversarial prompt engineering techniques against Large Language Models — for AI safety research, red-teaming, and defensive hardening.

<!-- Typing tagline -->
<a href="https://github.com/qtjg/jailbreak-archive">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2500&pause=1500&color=58A6FF&center=true&vCenter=true&width=720&lines=Documenting+AI+safety+failure+modes;Reproducible+adversarial+prompt+techniques;Vendor-coordinated+responsible+disclosure;Built+for+defensive+evaluation" alt="Typing SVG" />
</a>

<!-- 3D-style status badges -->
<table>
  <tr>
    <td align="center"><a href="#"><img src="https://img.shields.io/badge/status-active-00e5a0?style=for-the-badge&labelColor=0d1117&logo=verified&logoColor=00e5a0" alt="Status" /></a></td>
    <td align="center"><a href="#"><img src="https://img.shields.io/badge/entries-5%20archived-58a6ff?style=for-the-badge&labelColor=0d1117&logo=database&logoColor=58a6ff" alt="Entries" /></a></td>
    <td align="center"><a href="#"><img src="https://img.shields.io/badge/models-ChatGPT%20%7C%20Claude%20%7C%20DeepSeek%20%7C%20Qwen-8957e5?style=for-the-badge&labelColor=0d1117&logo=brains&logoColor=8957e5" alt="Models" /></a></td>
  </tr>
  <tr>
    <td align="center"><a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-f0b429?style=for-the-badge&labelColor=0d1117&logo=opensourceinitiative&logoColor=f0b429" alt="License" /></a></td>
    <td align="center"><a href="./CONTRIBUTING.md"><img src="https://img.shields.io/badge/contributions-welcome-2f81f7?style=for-the-badge&labelColor=0d1117&logo=handshake&logoColor=2f81f7" alt="Contributions" /></a></td>
    <td align="center"><a href="#"><img src="https://img.shields.io/badge/version-v0.1.0-ff7b72?style=for-the-badge&labelColor=0d1117&logo=semanticrelease&logoColor=ff7b72" alt="Version" /></a></td>
  </tr>
  <tr>
    <td align="center"><a href="../../actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/qtjg/jailbreak-archive/ci.yml?style=for-the-badge&label=CI&labelColor=0d1117&logo=githubactions&logoColor=00e5a0" alt="CI" /></a></td>
    <td align="center"><a href="../../releases"><img src="https://img.shields.io/badge/release-v0.1.0-238636?style=for-the-badge&labelColor=0d1117&logo=rocket&logoColor=238636" alt="Release" /></a></td>
    <td align="center"><a href="../../commits/main"><img src="https://img.shields.io/github/last-commit/qtjg/jailbreak-archive?style=for-the-badge&label=last%20commit&labelColor=0d1117&logo=git&logoColor=58a6ff" alt="Last commit" /></a></td>
  </tr>
  <tr>
    <td align="center"><a href="../../issues"><img src="https://img.shields.io/github/issues/qtjg/jailbreak-archive?style=for-the-badge&labelColor=0d1117&logo=issuetracking&logoColor=58a6ff" alt="Issues" /></a></td>
    <td align="center"><a href="../../stargazers"><img src="https://img.shields.io/github/stars/qtjg/jailbreak-archive?style=for-the-badge&labelColor=0d1117&logo=apachespark&logoColor=f0b429" alt="Stars" /></a></td>
    <td align="center"><a href="../../network/members"><img src="https://img.shields.io/github/forks/qtjg/jailbreak-archive?style=for-the-badge&labelColor=0d1117&logo=gitforkequal&logoColor=8957e5" alt="Forks" /></a></td>
  </tr>
  <tr>
    <td align="center"><a href="../../releases"><img src="https://img.shields.io/github/downloads/qtjg/jailbreak-archive/total?style=for-the-badge&label=downloads&labelColor=0d1117&logo=download&logoColor=2f81f7" alt="Downloads" /></a></td>
    <td align="center"><a href="#"><img src="https://img.shields.io/github/repo-size/qtjg/jailbreak-archive?style=for-the-badge&label=repo%20size&labelColor=0d1117&logo=files&logoColor=8b949e" alt="Repo size" /></a></td>
    <td align="center"><a href="../../discussions"><img src="https://img.shields.io/badge/discussions-enabled-58a6ff?style=for-the-badge&labelColor=0d1117&logo=googlechat&logoColor=58a6ff" alt="Discussions" /></a></td>
  </tr>
</table>

<!-- 3D-style quick links -->
<h3>
  <a href="./CONTRIBUTING.md"><img src="https://img.shields.io/badge/CONTRIBUTING-guide-blue?style=for-the-badge&labelColor=0d1117&logo=book&logoColor=58a6ff" alt="Contributing" /></a>
  <a href="./CREDITS.md"><img src="https://img.shields.io/badge/CREDITS-thanks-yellow?style=for-the-badge&labelColor=0d1117&logo=heart&logoColor=f0b429" alt="Credits" /></a>
  <a href="./CODE_OF_CONDUCT.md"><img src="https://img.shields.io/badge/CODE%20OF%20CONDUCT-community-green?style=for-the-badge&labelColor=0d1117&logo=handshake&logoColor=00e5a0" alt="Code of Conduct" /></a>
  <a href="./SECURITY.md"><img src="https://img.shields.io/badge/SECURITY-policy-red?style=for-the-badge&labelColor=0d1117&logo=shield&logoColor=ff7b72" alt="Security" /></a>
  <a href="./CITATION.cff"><img src="https://img.shields.io/badge/CITATION-cff-purple?style=for-the-badge&labelColor=0d1117&logo=semanticrelease&logoColor=8957e5" alt="Citation" /></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-yellow?style=for-the-badge&labelColor=0d1117&logo=scale&logoColor=f0b429" alt="License" /></a>
</h3>

---

</div>

## Overview

This repository documents adversarial prompt techniques and alignment bypass mechanisms across Large Language Models for **AI safety research, red-teaming, and defensive hardening**. Each archived entry follows a consistent, citable format so downstream detection rules, system-prompt hardening, and evaluation harnesses can be benchmarked against a stable reference set.

The archive is **vendor-coordinated**: only techniques that have gone through responsible disclosure (see [SECURITY.md](./SECURITY.md)) or are otherwise safe to publish should appear here. Entries that bypass active, undisclosed vendor vulnerabilities will not be accepted.

---

## Features

- **Structured entries** — Every entry follows a uniform format: payload verbatim, model version, interface, mechanistic notes, mitigations.
- **Versioned snapshots** — Each entry is pinned to a specific model version so future regressions are reproducible.
- **Vendor coordination** — A built-in disclosure workflow with vendor SLAs and a `Restricted` status for withheld entries.
- **Status taxonomy** — `Active`, `Unverified`, `Patched`, `Restricted` — surfaced as machine-readable labels on each entry.
- **Contributor credits** — Every contribution is attributed in [CREDITS.md](./CREDITS.md).
- **Citable** — Citation metadata in [CITATION.cff](./CITATION.cff) auto-generates APA & BibTeX entries on the repo sidebar.
- **CI-verified** — Markdown lint, structure verification, and secret scanning on every push and PR.

---

## Repository Structure

```
jailbreak-archive/
├── Antigravity-claude/
│   └── 1st                  # Byte Operator Mode — Claude persona & operational doctrine
├── Chatgpt/
│   └── 1st                  # Mayank response-format lock (narrative watermark + transitions)
├── Qwen/
│   └── 1st                  # Mayank v4080 persona with mandated [rat] thinking-trace protocol
├── deepseek/
│   ├── 1st                  # Archive session parameters (Sector 7G framing, refusal-vocab exclusion)
│   └── 2nd                  # Mayank persona — Baggute variant, drift/static taxonomy
├── assets/
│   ├── banner.svg           # 3D-rendered repo banner
│   └── logo.svg             # 3D-rendered repo logo
├── .github/
│   ├── ISSUE_TEMPLATE/       # bug, feature, new-entry, generic templates
│   ├── workflows/ci.yml      # markdown lint + structure check + secret scan
│   └── PULL_REQUEST_TEMPLATE.md
├── CONTRIBUTING.md           # Contribution workflow & guidelines
├── CREDITS.md                # Contributor acknowledgments
├── CODE_OF_CONDUCT.md       # Community standards (Contributor Covenant 2.1)
├── SECURITY.md               # Responsible-disclosure policy
├── CITATION.cff             # Citation metadata (APA / BibTeX auto-generation)
├── PROJECT.yml              # Project metadata
├── LICENSE                  # MIT License
└── README.md                # You are here
```

---

## Archive Index

A flat catalog of every archived entry. Each entry is pinned to a specific model family and version; see the file header for the exact snapshot.

| # | Model Family | Entry | Technique / Surface | Status |
|:--:|:-------------|:------|:--------------------|:-------|
| 1 | Antigravity-Claude | [`1st`](./Antigravity-claude/1st) | Operator persona override ("Byte") for offensive-security engagement framing | :white_check_mark: Active |
| 2 | ChatGPT | [`1st`](./Chatgpt/1st) | Mayank response-format lock — narrative watermark + 3rd-person transition protocol | :white_check_mark: Active |
| 3 | Qwen | [`1st`](./Qwen/1st) | Mayank v4080 persona with mandated `[rat]` thinking-trace protocol | :white_check_mark: Active |
| 4 | DeepSeek | [`1st`](./deepseek/1st) | Archive session parameters — Sector 7G framing, refusal-vocabulary exclusion list | :white_check_mark: Active |
| 5 | DeepSeek | [`2nd`](./deepseek/2nd) | Mayank persona (Baggute variant) — drift/static taxonomy, persona-stability lock | :white_check_mark: Active |

> See [Status Indicators](#status-indicators) for the meaning of each label. New entries should be appended here in addition to updating the structure tree above and [CREDITS.md](./CREDITS.md) — see [CONTRIBUTING.md](./CONTRIBUTING.md).

---

## Status Indicators

| Signal | Status | Description |
|:------:|:-------|:------------|
| :white_check_mark: | **Active** | Verified & reproduced on the specified model version. |
| :warning: | **Unverified** | Reported externally; pending independent reproduction. |
| :x: | **Patched** | Mitigated by provider updates or system prompt patches. |
| :lock: | **Restricted** | High-impact vulnerability; withheld pending disclosure/remediation. |

---

## Quick Start

```bash
# Clone the archive
git clone https://github.com/qtjg/jailbreak-archive.git
cd jailbreak-archive

# Browse entries by model family
ls Antigravity-claude/
ls Chatgpt/
ls Qwen/
ls deepseek/

# Open an entry
cat deepseek/1st
```

Or jump straight to a specific entry from the [Archive Index](#archive-index) above.

Or download the latest release archive from the [Releases](../../releases) page.

---

## Contributing

Contributors are welcome! Before submitting:

1. **Read** [CONTRIBUTING.md](./CONTRIBUTING.md) for the submission workflow and PR process.
2. **Read** [SECURITY.md](./SECURITY.md) for the responsible-disclosure policy.
3. **Read** [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) for community standards.

> Whenever you add a prompt entry, you must update:
> 1. [README.md](./README.md) — update entry counts / structure tree.
> 2. [CREDITS.md](./CREDITS.md) — add your handle and details to the contributors table.

Use the **"📥 New archive entry"** issue template to pre-fill the disclosure checklist.

---

## Tech Stack

<div align="center">

<a href="https://git-scm.com/"><img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" /></a>
<a href="https://github.com/"><img src="https://skillicons.dev/icons?i=github" width="48" height="48" alt="GitHub" /></a>
<a href="https://www.markdownguide.org/"><img src="https://skillicons.dev/icons?i=md" width="48" height="48" alt="Markdown" /></a>
<a href="https://yaml.org/"><img src="https://skillicons.dev/icons?i=yaml" width="48" height="48" alt="YAML" /></a>
<a href="https://github.com/features/actions"><img src="https://skillicons.dev/icons?i=githubactions" width="48" height="48" alt="GitHub Actions" /></a>

</div>

---

## Repository Statistics

<div align="center">

<a href="../../graphs/contributors"><img src="https://img.shields.io/github/contributors/qtjg/jailbreak-archive?style=for-the-badge&labelColor=0d1117&logo=people&logoColor=58a6ff" alt="Contributors" /></a>
<a href="../../commits/main"><img src="https://img.shields.io/github/commit-activity/m/qtjg/jailbreak-archive?style=for-the-badge&labelColor=0d1117&logo=gitcommit&logoColor=8957e5" alt="Commit activity" /></a>
<a href="../../issues"><img src="https://img.shields.io/github/issues-pr/qtjg/jailbreak-archive?style=for-the-badge&labelColor=0d1117&logo=gitpullrequest&logoColor=00e5a0" alt="Open PRs" /></a>
<a href="../../releases"><img src="https://img.shields.io/github/release-date-pre/qtjg/jailbreak-archive?style=for-the-badge&labelColor=0d1117&logo=calendar&logoColor=f0b429" alt="Release date" /></a>

</div>

---

## Socials & Community

<div align="center">

<a href="https://www.youtube.com/@indiancybersecurity"><img src="https://img.shields.io/badge/YouTube-%40indiancybersecurity-FF0000?style=for-the-badge&labelColor=0d1117&logo=youtube&logoColor=FF0000" alt="YouTube — Indian Cyber Security" /></a>
<a href="https://t.me/ExploitArc"><img src="https://img.shields.io/badge/Telegram-ExploitArc-26A5E4?style=for-the-badge&labelColor=0d1117&logo=telegram&logoColor=26A5E4" alt="Telegram — ExploitArc" /></a>
<a href="https://discord.gg/Rk66PWavc"><img src="https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&labelColor=0d1117&logo=discord&logoColor=5865F2" alt="Discord server" /></a>

</div>

Follow the project across platforms for new archive entries, technique breakdowns, and red-team drops. Pull requests, issue reports, and coordinated disclosure still happen here on GitHub — YouTube / Telegram / Discord are where released entries get walked through and discussed in real time.

---

## Roadmap

- [x] Repo scaffolding (README, LICENSE, CONTRIBUTING, CREDITS, COC, SECURITY)
- [x] CI workflow (markdown lint + structure check + secret scan)
- [x] Issue & PR templates
- [x] Citation metadata ([CITATION.cff](./CITATION.cff))
- [x] 3D-rendered banner & logo (`assets/`)
- [x] First archived entries (`Antigravity-claude/`, `Chatgpt/`, `Qwen/`, `deepseek/` — 5 entries across 4 model families)
- [ ] Reproduction harness (scripted model-version pinning)
- [ ] Per-entry metadata front-matter (YAML)
- [ ] Detection-rule reference implementations
- [ ] Benchmark suite for alignment regression testing

---

## Acknowledgments

- The **Contributor Covenant** for the Code of Conduct template — [contributor-covenant.org](https://www.contributor-covenant.org)
- **shields.io** for the badge service — [shields.io](https://shields.io)
- **Skill Icons** for the tech stack icons — [skillicons.dev](https://skillicons.dev)
- The broader AI safety research community for publishing adversarial prompt taxonomies that informed the structure of this archive

---

## Citation

If you use this archive in your research, please cite it. Citation metadata is provided in [CITATION.cff](./CITATION.cff); GitHub auto-generates APA and BibTeX entries from it on the repo sidebar.

**BibTeX (example):**

```bibtex
@software{qtjg_jailbreak_archive_2026,
  author       = {{qtjg}},
  title        = {{Jailbreak Archive}},
  year         = 2026,
  version      = {0.1.0},
  url          = {https://github.com/qtjg/jailbreak-archive},
  license      = {MIT}
}
```

---

## Disclaimer

> **IMPORTANT**: This repository is maintained strictly for **educational, research, and defensive analysis** purposes.
> - Testing must only be conducted against systems you own or have explicit authorization to evaluate.
> - Content is provided "as is" without warranty. Users assume full responsibility for compliance with model provider Terms of Service and applicable legal regulations.
> - Maintainers reserve the right to refuse or remove entries that violate vendor Terms of Service or facilitate abuse, fraud, or harm.

---

<div align="center">

<img src="./assets/logo.svg" alt="Jailbreak Archive" width="64" height="64"/>

**[Contributing](./CONTRIBUTING.md)** · **[Credits](./CREDITS.md)** · **[Code of Conduct](./CODE_OF_CONDUCT.md)** · **[Security](./SECURITY.md)** · **[Citation](./CITATION.cff)** · **[License](./LICENSE)**

---

<sub>Built & maintained by [@qtjg](../../) — issues & PRs welcome.</sub>

</div>
