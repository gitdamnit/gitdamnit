# Hey, I'm Evan. 👋

### Developer tools. AI workflows. Useful weird shit.

**Independent developer · HR technologist · Critical thinker · Unapologetic tinkerer**

I build software because something needs fixing, something could be easier, or something doesn't exist that absolutely should.

My background is in human resources, technical recruiting, and business process improvement. Somewhere along the way, I started turning problems I encountered into software projects. Now I build developer tools, AI-assisted applications, workflow systems, and whatever else seems worth figuring out.

**Don't ask why. Ask why not.**

---

## 📋 ProDoc Guard

**Portable Agent Skill + CLI · v0.1.0 · [GitHub release](https://github.com/gitdamnit/prodoc-guard)**

*Project documentation that doesn't drift into creative fiction.*

[ProDoc Guard](https://github.com/gitdamnit/prodoc-guard) helps keep product requirements, architectural decisions, and development status aligned with what's actually happening. It's vendor-neutral, designed to travel between AI coding agents and development environments rather than locking your project knowledge into one tool.

**Highlights:** Requirements and decisions · Project status · Documentation validation · Portable Agent Skill · CLI

---

## 😈 [I Hope It Offends You](https://github.com/gitdamnit/ihopeitoffendsyou)

**Insult generator** built solely to lower your self-esteem · My first ever successful web app build · Archived project showcase.

*An insult generator with absolutely no interest in being polite.*

A deliberately rude, real-time roasting app powered by a handwritten insult engine, not AI. Built with React, Express, and PostgreSQL because apparently even insults deserve a proper backend.

The original website is no longer online, but the [GitHub repository](https://github.com/gitdamnit/ihopeitoffendsyou) still has screenshots of the glorious nonsense.

**Highlights:** Handwritten roast engine · React · Express · PostgreSQL · Screenshots

---

## 🔌 OpenCode Plugins

Three independent plugins for **OpenCode V2**. Each works on its own, with its own installation, configuration, and release lifecycle. They're designed to coexist, not depend on one another.

### 🧠 [Checkpoint Orchestrator](https://github.com/gitdamnit/opencode-checkpoint-plugin)

**v2.0.0 · GitHub released**

*Pick up where you left off without losing your damn place.*

Failure-resilient task-state checkpointing for AI-assisted development. It stores progress, blockers, and recovery snapshots in session-isolated SQLite, so multiple development sessions can share a repository without overwriting each other's checkpoints.

**Highlights:** SQLite persistence · Session isolation · Snapshots · Restoration · Task continuity

### 💾 [Git That Shit](https://github.com/gitdamnit/opencode-git-that-shit)

**v0.3.0 · GitHub released**

*Because "Oh Shit Git" is what you say after the damage is done.*

Automatically makes recoverable snapshots of important configuration and agent-state files before risky operations. Its separate shadow Git repository keeps recovery history out of your normal project commits. Also available as a standalone `gts` CLI.

**Highlights:** Pre-operation snapshots · Config recovery · Shadow Git · Standalone CLI

### 🛡️ [Stranger Danger](https://github.com/gitdamnit/opencode-stranger-danger)

**v0.2.0 · GitHub released**

*Your secrets have no business traveling to somebody else's model.*

Scans for credentials and sensitive information at AI coding-agent boundaries, including prompts, tool outputs, and model requests. Provides redaction, auditing, and allowlisting while keeping ordinary file inspection read-only.

**Highlights:** 236 detection rules · Context protection · Redaction · Safe audit logs · Standalone CLI

> **Distribution note:** The versions above are available as GitHub releases. Their corresponding npm releases are still being prepared; the npm registry may serve older versions or no package yet.

---

## 🧪 [OpenCode Plugin Test Lab](https://github.com/gitdamnit/opencode-plugin-lab)

**v1.0.0 · Public GitHub repository**

*Test the plugin before the plugin tests your patience.*

A standalone Docker-based test environment for OpenCode plugins, with isolated runtime validation, multi-plugin compatibility checks, offline model simulation, security-oriented tests, and reproducible reports. Unlike the projects above, **the lab is a developer tool, not a loadable OpenCode plugin**.

Its default test suite runs without any of my plugins; an optional regression profile covers all three.

**Highlights:** Docker isolation · Generic manifests · Multi-plugin tests · Failure isolation · Repeatable reports

**Recent validation:** 76 passed, 0 failed, 5 capability skips against OpenCode 2.0.32. [View the repository](https://github.com/gitdamnit/opencode-plugin-lab).

---

## 🪄 [Bludit Wizard](https://github.com/gitdamnit/bludit-wizard)

**Native Bludit CMS plugin · v1.1.0 · [GitHub release](https://github.com/gitdamnit/bludit-wizard/releases/tag/v1.1.0) · GPL-3.0-only**

*Your intelligent Bludit publishing companion.*

Bludit Wizard brings AI-assisted writing and editing directly into Bludit's administration interface. Its **twelve guided tasks** cover page drafting, outlines and article ideas; improving, rewriting and proofreading existing content; SEO metadata, clarity and freshness audits; internal link suggestions; and contextual questions.

Bludit Wizard supports configurable OpenAI-compatible providers, searchable model discovery, and model testing. OpenRouter and LLM Gateway have been verified in live use. Changes to existing content require human review and explicit approval; analysis tasks are read-only.

**Highlights:** 12 AI workflows · Model discovery · OpenRouter & LLM Gateway · Original/proposed comparison · Read-only audits · Human-approved edits

**[Download v1.1.0](https://github.com/gitdamnit/bludit-wizard/releases/tag/v1.1.0)** · [Source & documentation](https://github.com/gitdamnit/bludit-wizard)

*Submitted to the official Bludit plugin directory: [PR #489](https://github.com/bludit/plugins-repository/pull/489), awaiting maintainer approval.*

---

## 🔌 Bludit Wizard MCP

**Model Context Protocol integration · Local edition implemented**

A separate MCP integration for accessing Bludit content functionality from compatible AI clients. Its shared core exposes nineteen tools for retrieving site information, working with pages, and reviewing controlled edits.

The local stdio edition requires no centrally hosted service; optional self-hosted HTTP support is under consideration.

**Highlights:** MCP tools · Local-first execution · Shared core · Reviewable edits · No mandatory cloud hosting

*Further client validation and public release preparation pending.*

---

## 🏋️ TRAVIS v3

**Training Resource Assistant for Vitality, Intake, and Strength · Private development**

Personal-training management software designed around the needs of an actual trainer. TRAVIS brings client profiles, assessments, workout programming, session records, measurements, and nutrition macro tracking together in one practical workspace.

Version 3 emphasizes trainer-controlled AI assistance, clear session records, progress visualization, equipment management, and printable workout programs. The idea is to reduce administration, not replace the trainer's judgment.

**Highlights:** Client management · Workout programming · Progress tracking · Session logs · PDF exports

*Version 3 is under active development and testing.*

---

## 🤝 HR Agent Assist

**HR decision-support application · [Public repository](https://github.com/gitdamnit/hr-agent-assist)**

An AI-assisted HR information tool centered on role-aware answers grounded in company policies, source documents, and relevant guidance.

The next development phase will narrow the scope around practical policy retrieval, cited answers, and understandable guidance rather than expanding into a full HR platform.

**Highlights:** Policy retrieval · Source citations · Role-aware guidance · Document search

---

## 👥 TalentOps Command Center

**Recruiting and onboarding platform · ATS prototype**

*A clearer way to manage hiring from application to onboarding.*

An applicant tracking and recruiting-operations prototype bringing candidate pipelines, job requisitions, onboarding tasks, communication drafts, and reporting into a unified workspace.

**Highlights:** Applicant tracking · Candidate management · Recruiting workflows · Onboarding · HR operations

*Further refinement planned.*

---

## 🔧 Ollama Model Forge

**Ollama configuration utility · Development to resume**

*Make local model customization less complicated.*

A developer utility for creating, configuring, and validating Ollama Modelfiles through a more approachable workflow: model parameters, system instructions, previews, and export for local use.

**Highlights:** Ollama · Local models · Modelfile configuration · Developer experience

*Existing project slated for completion.*

---

## ⚙️ Technologies & Tools

**Languages:** TypeScript · JavaScript · Python · PHP · SQL

**Frontend:** React · Tailwind CSS · HTML · CSS

**Backend & data:** Node.js · Express · PostgreSQL · SQLite · Drizzle ORM

**Infrastructure:** Linux · Docker · Git · GitHub Actions · Cloudflare

**AI & development:** OpenCode · Ollama · MCP · Agent Skills · OpenAI-compatible APIs

I use whatever fits the problem. I'm not interested in making every project justify the same stack.

---

## 💡 How I Approach Development

It usually starts with a problem.

**I have a problem. Someone else has a problem. Something pisses me off. Something takes too many steps. Something should be easier, faster, or more streamlined. Or I catch myself asking, "Why the hell doesn't this exist?"**

That's usually when I start building.

- **Don't ask why. Ask why not.** Challenge assumptions and try things.
- **Solve actual problems.** Useful beats elaborate.
- **Independent by design.** One tool shouldn't require an entire ecosystem.
- **Evidence over assumptions.** Test what happened, not what should have happened.
- **Humans stay in control.** Review consequential AI-assisted changes.
- **Documentation matters.** Decisions and project status should reflect reality.
- **Keep it practical.** If another tool already solves the problem, use it.

Sometimes that turns into a useful application. Sometimes it turns into an experiment. Occasionally it turns into something called Git That Shit.

---

## 🌱 Beyond the Terminal

When I'm not writing code or finding new things to automate, I'm usually growing something, experimenting with something, or learning an unrelated skill.

I cultivate citrus, including **Meyer lemons, calamondins, Bearss limes, and Key limes**.

I also cultivate unusual, rare ethnobotanical and entheogenic plants, including *Acacia confusa*, Hawaiian baby woodrose (*Argyreia nervosa*), and various *Datura* and *Atropa belladonna* cultivars.

More recently, I've gotten into **tattooing**. I'm practicing on synthetic skin, developing my technique, and learning the craft before eventually working on real skin.

Apparently, software development, rare plants, and tattooing weren't individually enough hobbies to keep me occupied.

---

## 🌐 Elsewhere

- **Personal website:** [evanzellner.com](https://evanzellner.com)
- **Projects portfolio:** [projects.evanzellner.com](https://projects.evanzellner.com)
- **Professional resume:** [resume.evanzellner.com](https://resume.evanzellner.com)
- **GitHub:** [@gitdamnit](https://github.com/gitdamnit)

*The personal website and portfolio are being developed.*

---

**Build something useful. Break assumptions. Fix what's broken. Repeat.**
