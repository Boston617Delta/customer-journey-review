# Customer Journey Clarity

A reusable AI skill for improving decisions across marketing pages, offers, onboarding, and service handoffs. It connects observed friction to concrete changes and useful outcomes, with attention to clear commitments, relevant proof, truthful status, and user control.

The skill works for service businesses, commerce, and software. It adapts to the business and the scope of the request rather than prescribing a universal funnel or visual style. Conditional guidance covers audience research, creative-to-offer alignment, adapting a swipe into a brief, and interpreting diagnostic metrics.

## Install in Codex

Clone this repository into your skills directory:

```sh
git clone https://github.com/Boston617Delta/customer-journey-clarity.git ~/.codex/skills/customer-journey-clarity
```

If that directory already exists, inspect it before updating it. Do not overwrite an existing local skill blindly. Environments with a custom skills directory can use that location instead.

## Install in Claude Code

With Git and Claude Code installed, run this in your terminal to make the skill available across your local projects:

```sh
mkdir -p ~/.claude/skills
git clone https://github.com/Boston617Delta/customer-journey-clarity.git ~/.claude/skills/customer-journey-clarity
```

For one project, run the following from that project's root instead:

```sh
mkdir -p .claude/skills
git clone https://github.com/Boston617Delta/customer-journey-clarity.git .claude/skills/customer-journey-clarity
```

Choose one location. If the destination already exists, inspect it before updating. For a clean personal clone of this repository, update with:

```sh
git -C ~/.claude/skills/customer-journey-clarity pull --ff-only
```

Start Claude Code and invoke:

```text
/customer-journey-clarity Review this landing page for offer clarity and useful next steps: <URL>
```

Keep `SKILL.md` and `references/` together. See [Anthropic's skill documentation](https://code.claude.com/docs/en/skills) for locations and invocation.

## Skill files

The entrypoint is [SKILL.md](SKILL.md). Supporting references are loaded only when relevant:

- [Decision checks](references/decision-checks.md)
- [Creative research](references/creative-research.md)
- [From reference to brief](references/swipe-to-brief.md)
- [Applying evidence across contexts](references/evidence-and-transfer.md)

The optional `agents/openai.yaml` supplies Codex display and invocation metadata.

## Use

In Codex, ask your agent to use `$customer-journey-clarity`. In Claude Code, use `/customer-journey-clarity`. Supply the page, flow, document, or customer journey you want reviewed, plus the audience, intended action, and business constraints when available.

The skill supports review, scoped improvement, and translating findings into a roadmap. It does not require a particular browser, analytics provider, or private research library. It does not authorize publishing or other external actions on its own.

## Evidence and examples

This repository contains original reusable guidance. Case-study notes, screenshots, client details, internal roadmaps, and the optional examples library are maintained separately and are not included in this repository or its history.

The guidance draws on [Growth.Design case studies](https://growth.design/case-studies), lessons from [Motion's Creative Strategy Bootcamp](https://motionapp.com/events/2026-creative-strategy-bootcamp/homebase/recordings), marketing psychology research, selected product teardowns, and advertising examples I've collected over the years. My approach is influenced by David Ogilvy's advertising principles and established ad formats for explaining benefits, demonstrating value, and making comparisons. Research findings, practitioner perspectives, and illustrative concepts are considered in their original context. This is an independent synthesis, with no affiliation or endorsement. The public package contains no course recordings, transcripts, decks, newsletter copies, or private swipe assets.

## License

The original skill text is available under the [MIT License](LICENSE). Third-party source material is not distributed or licensed by this repository.
