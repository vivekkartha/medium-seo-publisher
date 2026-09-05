# Medium SEO Publisher

Research keywords, write in your voice, and publish on Medium when you ask.

## Install

```bash
npx skills add https://github.com/vivekkartha/medium-seo-publisher
```

Choose your agent in the installer. To install it for every supported agent, add `--agent '*'`.

[View on skills.sh](https://skills.sh/vivekkartha/medium-seo-publisher/medium-seo-publisher)

**Manual setup:** copy this repository into your agent's skills directory. If your agent does not support skills, ask it to read `SKILL.md` and the linked files in `references/`.

## Use

> Use medium-seo-publisher to research a topic and prepare a Medium article. Match this writing sample: …

> Publish the approved article, member-only, with an Unsplash image. Do not email subscribers.

Prepares drafts by default. Publication and subscriber emails require explicit permission.

## What you get

- Keyword research with sources and independent checks.
- An article in your voice, with built-in editing checks. Humanizer is optional.
- SEO metadata, Medium topics, image guidance, and a measurement plan.
- Browser publishing and verification when requested and supported.

## Compatibility

Agent-neutral Markdown, usable by any agent that can read instructions and local reference files. No Codex or Claude runtime is required. `agents/openai.yaml` is optional UI metadata.

Live research needs connected data/search tools; exports also work. Publishing needs an authenticated browser tool. Installing this skill does not provide subscriptions or connect those tools. Compatibility with every agent has not been tested.

## Evidence

[Comparison with existing skills](references/competitive-evidence.md) · [Evaluation cases](evals/cases.md) · [Launch plan](LAUNCH.md)

Package validation passes; comparative performance testing is pending. No ranking or conversion guarantees.

Version 1.0.1 · Editorial profile 1 · MIT license
