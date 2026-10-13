<h1 align="center">heidegger.skill</h1>

<p align="center">海德格尔 · Martin Heidegger</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“Language is the house of being.”<br>— Martin Heidegger · <a href="https://www.beyng.com/pages/de/GA09/GA09.313.html">Letter on Humanism</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for equipment, technology, and finitude: begin with activities and uses, and examine how technical arrangements make the world available as a resource.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. I only noticed a tool when it broke. What does that reveal?

> Ordinarily the work, not the isolated tool, holds your attention. Breakdown reveals relations of use and coordination. This helps describe everyday experience; it does not prove that consciousness manufactures objects.

### 2. Is calling employees deployable resources merely a change of vocabulary?

> Examine the arrangements, not only the term. Do time, abilities, and relationships appear only as quantities to store or replace? Check the purposes of scheduling and alternative explanations; digital tools alone do not establish such a change.

## What is distilled

| Method | What it helps examine |
|---|---|
| Equipmental relations | Situate objects within uses, activities, and shared life. |
| Technology and revealing | Compare uses with ways of storing, calculating, and ordering things. |
| Finitude | Distinguish biological prediction, personal confrontation, and care for others. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/heidegger-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `heidegger-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/heidegger-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Martin Heidegger’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selections on equipment and finitude in Being and Time; passages from The Question Concerning Technology. The opening quotation is separately checked against the Letter on Humanism.

- [Source catalogue and reading ranges](source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://www.beyng.com/pages/de/GA09/GA09.313.html">Letter on Humanism</a>, GA 9, p. 313. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
