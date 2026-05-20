# FounderOS Skill

**AI-native startup operating system for Claude, Claude Code, Codex, and agentic founders**

FounderOS Skill exists to turn startup thinking into executable workflows that AI coding agents can run with you. Instead of vague advice, this repo gives prompts, templates, and stage-by-stage operating playbooks you can use immediately.

> FounderOS Skill is an independent open-source toolkit. It is not affiliated with or endorsed by Anthropic, OpenAI, Claude, Codex, Cursor, or any other platform vendor.

## Why this repo exists
Founders are shipping faster with AI, but speed without structure creates expensive mistakes. FounderOS helps you:
- validate demand before overbuilding,
- ship an MVP with clear boundaries,
- launch with instrumentation and risk controls,
- scale using systems that preserve velocity.

## Problems it solves
- Building before validating customer pain
- Letting agents create accidental complexity and technical debt
- Launching without measurement, security basics, or rollback plans
- Scaling with reactive chaos instead of repeatable operating systems

## The four stages
1. **Idea** — Problem clarity, customer hypothesis, and market pressure testing
2. **MVP** — Scope discipline, architecture decisions, and execution constraints
3. **Launch** — Readiness gates, telemetry, security checks, and GTM activation
4. **Scale** — PMF signal tracking, system hardening, org loops, and moats

## Quickstart: Claude Skill
1. Open `skill.md`.
2. Import it as a custom skill in your Claude workflow.
3. Start with `prompts/00-master-founderos-prompt.md`.
4. Generate stage artifacts into your project docs using files in `templates/`.

## Quickstart: Claude Code
1. Open this repository in Claude Code.
2. Load `CLAUDE.md` as project instructions.
3. Ask Claude Code to run one workflow at a time from `workflows/`.
4. Commit generated artifacts after human review.

## Quickstart: Codex
1. Open this repository in Codex.
2. Use `CODEX.md` as repository operating instructions.
3. Start with `prompts/00-master-founderos-prompt.md` and pass your startup context.
4. Use templates and workflows to produce auditable Markdown deliverables.

## Example workflows
- `workflows/idea-to-hypothesis.md`
- `workflows/hypothesis-to-mvp.md`
- `workflows/mvp-to-launch.md`
- `workflows/launch-to-scale.md`

## Example command / prompt snippets
```text
Run FounderOS Stage 1 (Idea):
- Use prompts/01-idea-stage.md
- Fill templates/problem-hypothesis.md and templates/customer-discovery-plan.md
- Return risks, assumptions, and a go/no-go recommendation.
```

```text
Run FounderOS Stage 2 (MVP):
- Use prompts/02-mvp-stage.md and prompts/07-mvp-scope.md
- Produce templates/mvp-scope.md and templates/architecture-brief.md
- Flag any scope bloat or security-critical shortcuts.
```

```text
Run FounderOS Stage 3 (Launch):
- Use prompts/03-launch-stage.md and prompts/08-security-review.md
- Produce templates/launch-readiness-checklist.md and templates/gtm-plan.md
- Include rollout metrics, incident triggers, and rollback criteria.
```

## Repository structure
```text
founderos-skill/
├── README.md
├── LICENSE
├── skill.md
├── CLAUDE.md
├── CODEX.md
├── prompts/
├── templates/
├── workflows/
└── examples/
```

## Who this is for
- Founder-operators building with AI coding agents
- Early-stage teams that need speed with governance
- Product and engineering leads operationalizing AI-assisted delivery

## What this is not
- Not a substitute for deep domain expertise
- Not a guarantee of product-market fit
- Not legal, financial, security, compliance, or investment advice

## Security and compliance disclaimer
This toolkit includes security prompts and checklists, but it does **not** replace professional security review, legal counsel, privacy assessment, or compliance audits. Always perform human review before production launches, especially when handling real user data, regulated workflows, payments, or sensitive integrations.

## Contributing
1. Fork the repo and create a feature branch.
2. Add or improve prompts, templates, workflows, or examples.
3. Keep content practical, testable, and vendor-neutral.
4. Submit a pull request with before/after value and usage notes.

## If this helps you ship faster
Star the repo, share it with another founder, and contribute one improvement that would have saved you a week.
