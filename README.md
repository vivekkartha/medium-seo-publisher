# Medium SEO Publisher

Find questions people search for, choose one your article can realistically compete for, and turn it into a Medium post that still sounds like you. Publish only when you ask.

It can research the opportunity, explain why a title fits it, write the complete article from your ideas and any writing sample, and handle Medium topics, image guidance, policy checks, and publishing.

## Install

```bash
npx skills add https://github.com/vivekkartha/medium-seo-publisher
```

Choose your agent in the installer. To install it for every supported agent, add `--agent '*'`.

Check that the repository exposes the skill before installing:

```bash
npx skills add https://github.com/vivekkartha/medium-seo-publisher --list
```

After installation, confirm that `medium-seo-publisher` appears for the selected agent:

```bash
npx skills list
```

For a global installation, also run `npx skills ls -g`. Start a new agent session if the installed skill does not appear immediately.

[View on skills.sh](https://skills.sh/vivekkartha/medium-seo-publisher/medium-seo-publisher)

**Manual setup:** copy this repository into your agent's skills directory. If your agent does not support skills, ask it to read `SKILL.md` and the linked files in `references/`.

## Use

> Use medium-seo-publisher to research a topic and prepare a Medium article. Match this writing sample: …

> Publish the approved article, member-only, with an Unsplash image. Do not email subscribers.

Prepares drafts by default. Publication and subscriber emails require explicit permission.

## What you get

- Search-topic research that shows what people look for and how difficult each topic may be to compete for.
- A complete article from your ideas and, when supplied, your writing sample, with built-in editing checks. Humanizer is optional.
- A recommended title with a plain-language explanation, plus a recheck if a later title changes the article's topic or promise.
- Aligned story and preview titles, proposed search metadata, Medium topics, image guidance, and a plan for checking results.
- Browser publishing and verification when requested and supported.

## Compatibility

Agent-neutral Markdown for agents that can load `SKILL.md` and its relative references. No Codex- or Claude-specific runtime is required for prepare mode. `agents/openai.yaml` is optional UI metadata.

Live research requires monthly volume and organic keyword difficulty from an approved provider. The skill starts with existing access, explains verified free usage that a login can unlock, offers trial or paid access as a choice, and then works through a current free-first provider list when Semrush is unavailable or payment is declined. It can use a connected tool, compatible export, logged-in provider session through a controllable browser, or a first-party public interface that exposes both required fields. If no free or user-approved paid route supplies complete metrics, it stops instead of inventing a recommendation from ordinary search. Publishing needs an authenticated browser tool. Installing this skill does not provide subscriptions or connect those tools. Compatibility with every agent has not been tested.

## Evidence

[Comparison with existing skills](references/competitive-evidence.md) · [Evaluation cases](evals/cases.md) · [Launch plan](LAUNCH.md)

Package structure was checked on 6 September 2026 with `quick_validate.py` from the Codex skill-creator package and `npx skills add . --list`. See the [review record](evals/review-2026-09-06.md). Behavioral and comparative performance evidence is reported separately and must not be inferred from package validity. No ranking or conversion guarantees.

Version 1.1.0 · Editorial profile 1 · MIT license
