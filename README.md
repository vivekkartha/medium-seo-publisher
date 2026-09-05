# Medium SEO Publisher

Find questions people search for, choose one your article can realistically compete for, and turn it into a Medium post that still sounds like you. Publish only when you ask.

It can research the opportunity, explain why a title fits it, write the complete article in your voice, and handle the description, Medium topics, image guidance, and publishing checks.

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

- Search-topic research that shows what people look for and how difficult each topic may be to compete for.
- A complete article in your voice, with built-in editing checks. Humanizer is optional.
- A recommended title with a plain-language explanation, plus a recheck if a later title changes the article's topic or promise.
- A search-friendly headline and description, Medium topics, image guidance, and a plan for checking results.
- Browser publishing and verification when requested and supported.

## Compatibility

Agent-neutral Markdown, usable by any agent that can read instructions and local reference files. No Codex or Claude runtime is required. `agents/openai.yaml` is optional UI metadata.

Live research requires monthly volume and keyword difficulty from Semrush or Ahrefs, with Moz Keyword Explorer as the fallback. The skill can use a connected tool, compatible export, or logged-in provider session through a controllable browser. If none of the three is accessible, it stops and asks for provider access instead of inventing a recommendation from ordinary search. Publishing needs an authenticated browser tool. Installing this skill does not provide subscriptions or connect those tools. Compatibility with every agent has not been tested.

## Evidence

[Comparison with existing skills](references/competitive-evidence.md) · [Evaluation cases](evals/cases.md) · [Launch plan](LAUNCH.md)

Package validation passes; comparative performance testing is pending. No ranking or conversion guarantees.

Version 1.0.6 · Editorial profile 1 · MIT license
