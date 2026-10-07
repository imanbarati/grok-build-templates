# Grok Build Templates

A snapshot of **Grok Build** templates as of 2026-10-07.

Two catalogs live under the same name:

1. **[GrokForge specs](https://templates.grok.me/templates)** — 22 app specs you copy and drop into [Grok Build](https://grok.com/?mode=build). This is the list most people mean.
2. **CLI starter packs** — `AGENTS.md` files, `.grokignore` patterns, and project scaffolds for the [Grok Build terminal agent](https://x.ai/build).

Grok **Bot** templates (`x.ai/bot/...`) are a different product. See [Related](#related).

Score on GrokForge is `3 × votes + opens`.

---

## 1. GrokForge — drop into Grok Build

Source: [templates.grok.me](https://templates.grok.me/templates) · 22 specs · 9 categories

| # | Template | Category | Author | What it does | Votes | Score | Opens |
|---|---|---|---|---|---:|---:|---:|
| 1 | [Competitive Research Desk](https://templates.grok.me/templates/competitive-research-desk) | Research | war.room | Paste a product. Get a war room: named rivals, pricing tells, and three gaps you can ship against this quarter. | 14.8k | 86.6k | 42.1k |
| 2 | [Code Review Agent](https://templates.grok.me/templates/code-review-agent) | Coding | diff.ghost | Paste a diff. Get the review a staff engineer would actually leave: blockers, nits, tests, merge call. | 12.6k | 76.8k | 38.9k |
| 3 | [Landing Copy Lab](https://templates.grok.me/templates/landing-copy-lab) | Marketing | copy.desk | Hero, proof, objection, CTA — three tones, then a sludge-strip pass that bans “unlock” and “seamless” by name. | 11.3k | 67.3k | 33.4k |
| 4 | [Brand Voice Kit](https://templates.grok.me/templates/brand-voice-kit) | Creative | copy.desk | Paste three samples. Get a do/don’t voice card and a playground that rewrites into register. | 9.9k | 57.7k | 28.1k |
| 5 | [Dungeon Master Table](https://templates.grok.me/templates/dungeon-master-table) | Fun | night.shift | A 5-room one-shot you can run tonight: boxed text, NPCs with secret wants, loot that is not a +1 sword. | 7.9k | 54.9k | 31.2k |
| 6 | [Weekly Ops Command](https://templates.grok.me/templates/weekly-ops-command) | Personal | ops.core | Sunday planning that becomes a real week: three rocks, a daily map, a parking lot, a Friday shutdown. | 8.6k | 50.5k | 24.6k |
| 7 | [X Thread Engine](https://templates.grok.me/templates/x-thread-engine) | Marketing | copy.desk | Turn a post or a thesis into a 6–10 beat thread with a hook, a 280-char standalone, and a ratio-bait warning. | 5.8k | 39.6k | 22.1k |
| 8 | [Source-Cited Briefing](https://templates.grok.me/templates/source-cited-briefing) | Research | war.room | A one-page brief that will not hallucinate a citation. Unsourced claims are marked UNVERIFIED. | 6.4k | 37.5k | 18.2k |
| 9 | [Inbox Triage Agent](https://templates.grok.me/templates/inbox-triage-agent) | Ops | ops.core | Paste a pile of mail. Get act / wait / fyi / archive, plus a short draft for anything that needs a human today. | 5.1k | 31.8k | 16.4k |
| 10 | [Meeting Notes Distiller](https://templates.grok.me/templates/meeting-notes-distiller) | Ops | ops.core | Dump a transcript. Get a 5-line recap, decisions, owners, and a paste-ready recap email. | 4.7k | 29k | 14.9k |
| 11 | [SaaS Scaffold Spec](https://templates.grok.me/templates/saas-scaffold-spec) | Coding | diff.ghost | Interview yourself once. Emit a Phase-1 Grok Build prompt with screens, data, empty states, and a hard cut line. | 4.3k | 25.7k | 12.8k |
| 12 | [Explain Like I’m Curious](https://templates.grok.me/templates/explain-like-im-curious) | Education | chalk.line | One hard idea, three altitudes — curious 12-year-old, competent adult, practitioner — plus the common wrong take. | 3.5k | 24.7k | 14.1k |
| 13 | [Roast My Stack](https://templates.grok.me/templates/roast-my-stack) | Fun | night.shift | Paste your tools. Get a roast that names names, then one serious architecture note and one thing to delete. | 2.4k | 22.7k | 15.4k |
| 14 | [Lesson Plan Forge](https://templates.grok.me/templates/lesson-plan-forge) | Education | chalk.line | A timed 45-minute lesson: hook, teach, practice, exit ticket, analog variant, misconceptions to watch for. | 3.8k | 22.7k | 11.2k |
| 15 | [Personal CRM Lite](https://templates.grok.me/templates/personal-crm-lite) | Personal | ops.core | People you owe a message — name, last touch, next nudge, one-line context. No Salesforce energy. | 3.2k | 19.2k | 9.6k |
| 16 | [SEO Brief Builder](https://templates.grok.me/templates/seo-brief-builder) | Marketing | war.room | Editor-ready brief: intent, outline, entities, title/meta under limits, and a “do not write” list. | 2.9k | 17.5k | 8.9k |
| 17 | [Bug Repro Harness](https://templates.grok.me/templates/bug-repro-harness) | Coding | — | Turn “it broke” into environment, numbered steps, expected vs actual, three causes, and a failing test. | 2.6k | 16k | 8.1k |
| 18 | [ASCII Poster Studio](https://templates.grok.me/templates/ascii-poster-studio) | Creative | — | Type a title. Live phosphor stage, box frames, palettes, copy as text, download as SVG. Keyboard-first. | 2.2k | 16.8k | 10.2k |
| 19 | [Agent Eval Bench](https://templates.grok.me/templates/agent-eval-bench) | Experimental | — | Eight cases, two system prompts, a rubric (follow, brevity, citations, refusal). Side-by-side, saved locally. | 1.8k | 10.7k | 5.4k |
| 20 | [MCP Tool Spec Writer](https://templates.grok.me/templates/mcp-tool-spec-writer) | Experimental | night.shift | Describe a capability. Get a name, JSON schema, error codes, example calls, and a danger warning on unscoped writes. | 1.4k | 8.6k | 4.3k |
| 21 | [Flat PDF to Fillable Form](https://templates.grok.me/templates/flat-pdf-to-fillable-form) | Ops | — | Drop a scanned or flat PDF. Get a fillable form with every field named and checked. | 0 | 0 | 0 |
| 22 | [Grok Tshirt Store Owner](https://templates.grok.me/templates/grok-tshirt-store-owner) | Marketing | Chris Slowik | Run a full ecomm store: design, promote, fulfill, ads, performance. | 0 | 0 | 0 |

### By category

| Category | Templates |
|---|---|
| Research | Competitive Research Desk, Source-Cited Briefing |
| Coding | Code Review Agent, SaaS Scaffold Spec, Bug Repro Harness |
| Marketing | Landing Copy Lab, X Thread Engine, SEO Brief Builder, Grok Tshirt Store Owner |
| Creative | Brand Voice Kit, ASCII Poster Studio |
| Personal | Weekly Ops Command, Personal CRM Lite |
| Fun | Dungeon Master Table, Roast My Stack |
| Ops | Inbox Triage Agent, Meeting Notes Distiller, Flat PDF to Fillable Form |
| Education | Lesson Plan Forge, Explain Like I’m Curious |
| Experimental | Agent Eval Bench, MCP Tool Spec Writer |

### How to use a spec

1. Open the template page on [GrokForge](https://templates.grok.me/templates).
2. Copy the spec (or use **Open in Grok Build**).
3. Paste it into [Grok Build](https://grok.com/?mode=build) as the first message.

Machine-readable copy: [`templates.json`](templates.json).

---

## 2. Grok Build CLI starter packs

These are files you drop into a repo so the [terminal agent](https://x.ai/build) behaves. They are **not** the GrokForge app specs above.

From [DominikTobureto/awesome-grok-build](https://github.com/DominikTobureto/awesome-grok-build):

### AGENTS.md templates

| Template | Best for |
|---|---|
| `AGENTS.fullstack.md` | SaaS apps, dashboards, product builds |
| `AGENTS.library.md` | Open-source packages and SDKs |
| `AGENTS.docs.md` | Docs-heavy repos, awesome lists, knowledge bases |
| `AGENTS.security.md` | Security-sensitive codebases and audit workflows |

### Project templates

| File | Purpose |
|---|---|
| `templates/grokignore.default` | Safe default ignore patterns |
| `templates/grokignore.node` | Node / TypeScript projects |
| `templates/grokignore.python` | Python, venvs, notebooks, caches |
| `templates/python-fullstack` | Python full-stack starter + AGENTS.md |
| `templates/fastapi` | FastAPI service pack (API, DB, tests, security) |
| `templates/nextjs` | Next.js App Router pack |
| `examples/one-prompt-saas.md` | One-prompt SaaS scaffold request |

### Official CLI templates (in `xai-org/grok-build`)

The official [xai-org/grok-build](https://github.com/xai-org/grok-build) repo ships agent prompt files under `crates/codegen/xai-grok-agent/templates/` (`prompt.md`, `subagent_prompt.md`, `apply_patch_prompt.md`). Those are internal harness prompts, not user-facing app starters.

---

## Related

| What | Where |
|---|---|
| GrokForge marketplace | https://templates.grok.me |
| Grok Build (web app builder) | https://grok.com/?mode=build |
| Grok Build (terminal CLI) | https://x.ai/build |
| Official CLI source | https://github.com/xai-org/grok-build |
| CLI community pack | https://github.com/DominikTobureto/awesome-grok-build |
| Grok Bot templates (different product) | https://x.ai/bot/guides/templates-for-grok-bot |
| Awesome Grok Bot templates | https://github.com/lroolle/awesome-grokbot-templates |
| Grok Bot marketplace | https://x.ai/bot/marketplace |

---

## Snapshot

- Captured: 2026-10-07
- GrokForge claimed count: 22 specs, 9 categories
- This repo is a catalog, not the templates themselves. Specs remain on GrokForge; starter packs remain in their upstream repos.
