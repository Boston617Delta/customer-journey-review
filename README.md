# Customer Journey Clarity

A reusable AI skill for improving decisions across marketing pages, offers, onboarding, and service handoffs. It connects observed friction to concrete changes and useful outcomes, with attention to clear commitments, relevant proof, truthful status, and user control.

The skill works for service businesses, commerce, and software. It adapts to the business and the scope of the request rather than prescribing a universal funnel or visual style.

## Install in Codex

Clone this repository into your skills directory:

```sh
git clone https://github.com/Boston617Delta/customer-journey-clarity.git ~/.codex/skills/customer-journey-clarity
```

If that directory already exists, inspect it before updating it. Do not overwrite an existing local skill blindly. Environments with a custom skills directory can use that location instead.

The entrypoint is [SKILL.md](SKILL.md). Supporting decision checks are in [references/decision-checks.md](references/decision-checks.md). The optional `agents/openai.yaml` supplies display and invocation metadata.

## Use

Ask your agent to use `$customer-journey-clarity` with the page, flow, document, or customer journey you want reviewed. Provide the audience, intended action, and business constraints when available.

The skill supports review, scoped improvement, and translating findings into a roadmap. It does not require a particular browser, analytics provider, or private research library. It does not authorize publishing or other external actions on its own.

## Evidence and examples

This repository contains original reusable guidance. Case-study notes, screenshots, client details, internal roadmaps, and the optional examples library are maintained separately and are not included in this repository or its history.

The guidance was informed by a review of [Growth.Design case studies](https://growth.design/case-studies). This is an independent synthesis, with no affiliation or endorsement. Historical examples, proposed redesigns, and reported results should retain their context when used.

## License

The original skill text is available under the [MIT License](LICENSE). Third-party source material is not distributed or licensed by this repository.
