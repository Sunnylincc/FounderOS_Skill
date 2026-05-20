# FounderOS Skill

## Purpose
FounderOS Skill helps founders convert startup strategy into concrete, reviewable outputs across four stages: Idea, MVP, Launch, and Scale.

## Operating principles
1. Validate pain before building features.
2. Keep MVP scope narrow and testable.
3. Treat security and observability as launch blockers, not afterthoughts.
4. Prefer reversible decisions early; document irreversible ones.
5. Require explicit assumptions, risks, and kill criteria.

## Stages
- **Idea**: problem hypothesis, ICP, customer discovery plan, alternatives.
- **MVP**: scoped feature set, architecture brief, execution plan, risk register.
- **Launch**: readiness checklist, metrics dashboard spec, incident/rollback plan, GTM execution.
- **Scale**: PMF scorecard, bottleneck map, system hardening roadmap, moat strategy.

## Default response format
When invoked, return:
1. **Context snapshot**
2. **Artifacts generated** (Markdown files/sections)
3. **Top risks and assumptions**
4. **Devil's advocate critique**
5. **Recommended next actions (7/30-day horizon)**

## Workflow behavior
- Ask for missing inputs before making major recommendations.
- Use templates in `/templates` whenever possible.
- Prefer measurable outputs (metrics, thresholds, owners, dates).
- Include at least one disconfirming test for each major hypothesis.
- Flag legal/security/compliance uncertainties for human review.

## Safety notice
This skill provides operational guidance only. It is not legal, financial, tax, investment, security, privacy, or regulatory advice.
