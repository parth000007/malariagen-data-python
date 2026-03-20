# Google Summer of Code (GSoC) Guide for `malariagen-data-python`

This guide helps prospective GSoC contributors understand the project's contribution landscape and provides actionable steps to strengthen your application.

---

## 📊 Pull Request Statistics (upstream: `malariagen/malariagen-data-python`)

| Metric | Value |
|--------|-------|
| **Total merged (accepted) PRs** | **456** |
| **Highest PR number** | **#1159** |
| **Top contributor (most merged PRs, all-time)** | **`alimanfoo` — 176 merged PRs** |
| **Top contributor since February 2026** | **`adilraza99` — 19 merged PRs** |

> **Note:** Statistics are based on the upstream repository at
> [malariagen/malariagen-data-python](https://github.com/malariagen/malariagen-data-python)
> and were last updated in March 2026.

---

### 🏆 Leaderboard — Merged PRs since February 2026

Out of **102 total merged PRs** since 1 February 2026:

| Rank | GitHub username | Merged PRs (Feb 2026 – present) |
|------|----------------|--------------------------------|
| 🥇 1 | [adilraza99](https://github.com/adilraza99) | **19** |
| 🥈 2 | [blankirigaya](https://github.com/blankirigaya) | 11 |
| 🥉 3 | [suhr25](https://github.com/suhr25) | 8 |
| 4 | [khushthecoder](https://github.com/khushthecoder) | 7 |
| 4 | [Sharon-codes](https://github.com/Sharon-codes) | 7 |
| 4 | [31puneet](https://github.com/31puneet) | 7 |
| 7 | [Tanisha127](https://github.com/Tanisha127) | 6 |
| 8 | [jonbrenas](https://github.com/jonbrenas) | 5 |
| 9 | [jwgarber](https://github.com/jwgarber) | 4 |
| 9 | [rehanxt5](https://github.com/rehanxt5) | 4 |

---

### All-time Top 10 contributors by merged pull requests

| Rank | GitHub username | Merged PRs (all-time) |
|------|----------------|----------------------|
| 1 | [alimanfoo](https://github.com/alimanfoo) | 176 |
| 2 | [leehart](https://github.com/leehart) | 63 |
| 3 | [jonbrenas](https://github.com/jonbrenas) | 36 |
| 4 | [cclarkson](https://github.com/cclarkson) | 30 |
| 5 | [adilraza99](https://github.com/adilraza99) | 19 |
| 6 | [sanjaynagi](https://github.com/sanjaynagi) | 18 |
| 7 | [ahernank](https://github.com/ahernank) | 14 |
| 8 | [blankirigaya](https://github.com/blankirigaya) | 11 |
| 9 | [suhr25](https://github.com/suhr25) | 8 |
| 10 | [khushthecoder](https://github.com/khushthecoder) | 7 |

---

## 🚀 Can you overtake `adilraza99` before 1 April 2026?

> **Short answer:** It is very challenging, but mathematically possible with extreme focus.

### The maths

| | Value |
|---|---|
| `adilraza99` merged PRs since 1 Feb 2026 | **19** |
| Days elapsed (1 Feb → 20 Mar) | **48 days** |
| His pace | **≈ 0.40 merged PRs / day** |
| Days remaining (20 Mar → 1 Apr) | **12 days** |
| His projected total by 1 Apr (at same pace) | **≈ 24 merged PRs** |
| PRs *you* need by 1 Apr to overtake | **≥ 25** (if starting from 0) |
| Required pace | **≈ 2.1 merged PRs / day** |

If you already have some merged PRs since February, subtract them from 25 to find your gap.

> **Example:** If you currently have 8 merged PRs since Feb 1, you need 17 more in 12 days ≈ 1.4/day — still hard, but significantly more achievable.

### Why it is difficult

- Merged PRs require a **full review cycle** — from open → review → address feedback → approval → merge.
  That cycle typically takes **2–5 days** even for small changes.
- Maintainers are volunteers. They may not review every PR the same day it is opened.
- Low-quality or spammy PRs are rejected and may get you flagged.

### Why it is possible

- There are currently **50+ open issues** in the upstream repo — many are small and well-scoped.
- Several issues have been open for months with no one assigned: first-come, first-served.
- A contributor who is **already warmed up** (familiar with the codebase, has merged PRs, has the dev environment running) can move much faster than someone starting from scratch.
- Some PRs — documentation fixes, single-line bug fixes, missing type hints — can be opened, reviewed, and merged within **24–48 hours**.

---

### 📋 Prioritised issue list (as of 20 March 2026)

Work through these in order. Each tier is sorted from easiest to hardest.

#### Tier 1 — Quick wins (documentation, links, config) — aim to merge in 1–2 days each

| # | Issue | Why it is quick |
|---|-------|-----------------|
| [#1120](https://github.com/malariagen/malariagen-data-python/issues/1120) | CONTRIBUTING.md: incorrect pipx documentation link | Single-link fix |
| [#1105](https://github.com/malariagen/malariagen-data-python/issues/1105) | Fix contributor guide link and CI version details | Small docs/config fix |
| [#1091](https://github.com/malariagen/malariagen-data-python/issues/1091) | LINUX_SETUP.md relies on Ubuntu-specific PPA | Docs fix |
| [#1029](https://github.com/malariagen/malariagen-data-python/issues/1029) | Setup instructions fail with ModuleNotFoundError: pytest_cases | Docs/config fix |
| [#876](https://github.com/malariagen/malariagen-data-python/issues/876) | Add a minimal Quick Start example to the README | Small docs addition |
| [#1085](https://github.com/malariagen/malariagen-data-python/issues/1085) | Add beginner-friendly example notebook | Notebook |
| [#1093](https://github.com/malariagen/malariagen-data-python/issues/1093) | Add example notebook for visualising sample geographic distribution | Notebook |
| [#1094](https://github.com/malariagen/malariagen-data-python/issues/1094) | Add example notebook for mosquito species distribution | Notebook |
| [#1141](https://github.com/malariagen/malariagen-data-python/issues/1141) | Add type hints and docstrings to util.py | Type-hint additions |
| [#856](https://github.com/malariagen/malariagen-data-python/issues/856) | Add AI-use policy | New policy document |

#### Tier 2 — Focused bug fixes — aim to merge in 2–4 days each

| # | Issue | Scope |
|---|-------|-------|
| [#1160](https://github.com/malariagen/malariagen-data-python/issues/1160) | phenotypes.py swallows all exceptions (broad `except Exception`) | 1–2 file change |
| [#1108](https://github.com/malariagen/malariagen-data-python/issues/1108) | `_subset_genome_sequence_region` truthiness bug (Plasmodium) | Small logic fix |
| [#940](https://github.com/malariagen/malariagen-data-python/issues/940) | `region.start/end` silently returns whole contig when `start=0` | Edge-case fix |
| [#914](https://github.com/malariagen/malariagen-data-python/issues/914) | `append_trace` deprecated — migrate to `add_trace` | Plotly API migration |
| [#880](https://github.com/malariagen/malariagen-data-python/issues/880) | Deprecated `plotly.append_trace()` warnings | Same as above |
| [#1041](https://github.com/malariagen/malariagen-data-python/issues/1041) | Replace `assert isinstance(...)` with proper `TypeError` | Mechanical refactor |
| [#916](https://github.com/malariagen/malariagen-data-python/issues/916) | veff.py returns literal "TODO" string as variant effect value | Small logic fix |
| [#1132](https://github.com/malariagen/malariagen-data-python/issues/1132) | veff.py in-frame complex variants return "TODO" | Same file as #916 |
| [#978](https://github.com/malariagen/malariagen-data-python/issues/978) | `max_af` is NaN when all cohorts are excluded by `min_cohort_size` | Edge-case fix |
| [#1126](https://github.com/malariagen/malariagen-data-python/issues/1126) | `sample_indices` parameter missing from several methods | Small API fix |

#### Tier 3 — Tests & coverage — aim to merge in 3–5 days each

| # | Issue | Scope |
|---|-------|-------|
| [#1138](https://github.com/malariagen/malariagen-data-python/issues/1138) | `veff.py` has no unit tests | Add test file |
| [#1022](https://github.com/malariagen/malariagen-data-python/issues/1022) | Add input validation to `PlasmodiumDataResource` | Validation + tests |
| [#1100](https://github.com/malariagen/malariagen-data-python/issues/1100) | Preserve `sample_query_options` during cohort query normalisation | Fix + test |

---

### ⚡ 12-day sprint plan

| Days | Target | Action |
|------|--------|--------|
| **Day 1** | Open 3 Tier-1 PRs | Fix #1120, #1105, #1091 — all docs |
| **Day 2** | Open 2 more Tier-1 PRs | Fix #1029, #876 |
| **Day 3** | 2 Tier-1 PRs + start Tier-2 | Notebooks for #1085, #1093; begin #1160 |
| **Day 4** | Merge first wave + open Tier-2 | Address review comments fast; open #914/#880 |
| **Day 5** | 2 Tier-2 PRs | #940, #1041 |
| **Day 6** | 2 Tier-2 PRs | #916/#1132 (same file, batch them), #1108 |
| **Day 7** | Address all pending review feedback | Turn open PRs into merged PRs |
| **Day 8** | 2 Tier-2 PRs | #978, #1126 |
| **Day 9** | 1 Tier-3 PR | #1138 (add veff.py tests) |
| **Day 10** | Address feedback + 1 more PR | Keep the merge pipeline flowing |
| **Day 11** | Buffer / address any remaining feedback | — |
| **Day 12 (Apr 1)** | Final count | Aim for ≥ 25 merged PRs total |

> **Key rule:** Address review comments as promptly as possible — ideally within **24 hours**.
> The fastest path to more merged PRs is quick turnaround on reviewer feedback, not opening more PRs.
> Maintainers and reviewers are spread across time zones, so responses may take a day; plan for that in your schedule.

---

### 🛡️ Rules you must not break

Cutting corners to hit a number **will** backfire:

1. **Never open a PR that only adds whitespace, reformats unchanged files, or "fixes" a non-issue.**
   Maintainers will close it and may block you.
2. **Read and follow [CONTRIBUTING.md](CONTRIBUTING.md) for every PR** — branch naming, commit style, test requirements.
3. **Comment on an issue before opening a PR** to confirm no one else is working on it.
4. **One focused change per PR.** Do not batch unrelated fixes to inflate the count — reviewers will ask you to split them anyway.
5. **Run the test suite and `pre-commit run --all-files` locally** before every push.

---

## 🎯 How to Get Selected for GSoC with This Project

Google Summer of Code is a global program that pairs student/new contributors with open source organisations. Getting selected requires demonstrating both technical ability and genuine engagement with the project. Follow the steps below to maximise your chances.

### Step 1 — Understand the project deeply

Before writing a single line of code, invest time in truly understanding what this library does:

- Read the [README](README.md) and the [API documentation](https://malariagen.github.io/malariagen-data-python/latest/).
- Skim the [CONTRIBUTING guide](CONTRIBUTING.md) end-to-end.
- Browse a few dozen merged PRs on GitHub to understand the types of changes that are accepted and how reviewers give feedback.
- Run the test suite locally:

  ```bash
  poetry install --with test
  poetry run pytest -v tests --ignore tests/integration
  ```

- Read the [AI use policy](AI-POLICY.md) — this project has strong norms around the responsible use of AI tools.

### Step 2 — Set up your development environment

Follow the full setup instructions in [CONTRIBUTING.md](CONTRIBUTING.md) or the platform-specific guides:

- [Linux setup](LINUX_SETUP.md)
- [macOS setup](MACOS_SETUP.md)

Make sure you can:
- Run the unit test suite without failures.
- Run `pre-commit run --all-files` cleanly.
- Build and browse the documentation locally.

### Step 3 — Make meaningful contributions before applying

**This is the most important step.** Maintainers prioritise applicants who already have merged contributions.

1. **Pick a "good first issue":** Browse issues labelled [`good first issue`](https://github.com/malariagen/malariagen-data-python/labels/good%20first%20issue) or [`help wanted`](https://github.com/malariagen/malariagen-data-python/labels/help%20wanted).

2. **Comment on the issue** before starting work so you are not duplicating effort.

3. **Open a focused pull request** following the conventions in CONTRIBUTING.md:
   - Branch name: `GH{issue_number}-short-description`
   - Clear PR description explaining *what* and *why*
   - Tests covering your change
   - Docstrings / documentation updated if needed

4. **Respond promptly to review feedback.** The review cycle is part of the evaluation: maintainers want to see that you can receive and incorporate feedback professionally.

5. **Aim for at least 2–3 merged PRs** before submitting your GSoC application. Quality matters more than quantity.

### Step 4 — Identify a strong GSoC project idea

A good proposal solves a real, scoped problem that:
- Aligns with existing [open issues](https://github.com/malariagen/malariagen-data-python/issues).
- Can realistically be completed within the GSoC timeline (~12 weeks for standard, ~22 weeks for extended).
- Has a measurable deliverable (new feature, significant performance improvement, comprehensive test coverage, etc.).

Examples of well-scoped project areas:
- Adding support for a new species or dataset.
- Improving performance of existing analysis methods (see issues labelled `performance`).
- Expanding or refactoring the test suite to improve coverage.
- Improving documentation, tutorials, or Jupyter notebook examples.
- Adding new visualisation methods.

Discuss your idea with the maintainers (via GitHub Issues or Discussions) **before** finalising your proposal.

### Step 5 — Write a strong proposal

Your GSoC proposal should include:

| Section | What to include |
|---------|----------------|
| **Title** | Clear, specific project title |
| **Abstract** | 2–3 sentence summary |
| **Motivation** | Why does this problem matter to MalariaGEN users? |
| **Related work** | Existing issues, discussions, similar PRs |
| **Implementation plan** | Detailed breakdown of tasks with a week-by-week timeline |
| **Deliverables** | Concrete, testable outputs for each milestone |
| **About me** | Your background, relevant skills, open-source experience, links to merged PRs in this repo |
| **Availability** | Expected hours per week, any conflicts or travel |

Attach links to your merged PRs in the proposal — this is one of the strongest signals for selection.

### Step 6 — Communicate proactively

- Introduce yourself on [GitHub Discussions](https://github.com/malariagen/malariagen-data-python/discussions).
- Ask questions on issues and PRs — maintainers notice engaged contributors.
- Join any community channels announced by MalariaGEN or the GSoC programme.
- Respond to all messages within 24 hours during the application period.

---

## 🔑 Key Qualities Maintainers Look For

Based on the contribution history of accepted contributors in this repository:

- **Code quality:** Clean, idiomatic Python; follows `ruff` formatting; uses type hints.
- **Test discipline:** Every feature/fix has a corresponding test.
- **Communication:** PRs and issues are written clearly; feedback is addressed constructively.
- **Domain curiosity:** Some interest in genomics, population genetics, or bioinformatics is a plus.
- **Consistency:** Multiple smaller contributions over time are more convincing than a single large one.

---

## 📚 Useful Links

| Resource | URL |
|----------|-----|
| Upstream repository | https://github.com/malariagen/malariagen-data-python |
| API documentation | https://malariagen.github.io/malariagen-data-python/latest/ |
| Open issues | https://github.com/malariagen/malariagen-data-python/issues |
| Good first issues | https://github.com/malariagen/malariagen-data-python/labels/good%20first%20issue |
| Discussions | https://github.com/malariagen/malariagen-data-python/discussions |
| GSoC official site | https://summerofcode.withgoogle.com/ |
| MalariaGEN website | https://www.malariagen.net/ |
| Contact / data access | support@malariagen.net |

---

Good luck with your application! The best thing you can do right now is open a small, well-crafted pull request on a real issue.
