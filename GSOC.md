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
