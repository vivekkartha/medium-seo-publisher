---
name: medium-seo-publisher
description: Research attainable keywords and prepare voice-matched Medium articles with SEO metadata, topics, and conversion measurement. Publish through Medium only when explicitly requested. Use for a Medium article workflow, not general technical website audits.
metadata:
  version: "1.0.1"
  editorial-profile: "1"
---

# Medium SEO Publisher

Turn a topic into an evidence-backed Medium article and a measurable publishing experiment. Default to preparing a reviewable package. Publishing requires an explicit request in the current task; creating or invoking this skill does not grant that permission.

## Agent compatibility

These are portable Markdown instructions. Use the current host's tools for files, search, browser interaction, and scheduling; no particular agent API, filesystem root, or slash-command syntax is required. The optional agents/openai.yaml file only supplies UI metadata for hosts that understand it; other hosts may ignore it.

On hosts without skill discovery, the user can provide SKILL.md and its relative reference files directly. Resolve references relative to this package. If a required tool is absent, complete the supported work and state the precise remaining limitation. Text-only agents can prepare from supplied evidence; live research requires search/data access, and publishing requires an authenticated browser tool. Do not claim every host has been tested.

## Quick preflight

Reuse session context. Check only what affects the next action; keep routine checks out of the conversation.

- Establish the topic or existing article, audience, market/language, and primary outcome. Distinguish engaged reads, followers, signups, and revenue. Ask only about material gaps. Preserve any existing access/paywall preference.
- Inspect available tools for keyword data and browser access. Prefer connected bulk research tools; supplied exports and logged-in provider UIs are valid fallbacks. Installing a skill does not connect its MCP server. Do not install services, buy credits, or assume paid API access from a website login.
- Locate an available Humanizer through the host's skill catalog or configured skill directories. Inspect its metadata and instructions, without scanning unrelated personal files. Use declared version plus capabilities; matching an upstream version alone is insufficient. Read [editorial.md](references/editorial.md) and load missing guidance before a single integrated rewrite. No automatic download or replacement.
- Check Medium account identity only for requested editor work. Before publication, verify the actual destination and current publish settings.

## Research with bounded effort

Read [research.md](references/research.md). Reuse recent compatible observations when appropriate; date them and refresh finalists when the decision depends on current competition.

Prefer one bulk discovery request and one bulk metrics request, then inspect the viable finalists. With OpenSEO, discover callable schemas for research_keywords, get_keyword_metrics, and get_serp_results; use their current limits rather than hardcoded assumptions. Without OpenSEO, use another connected provider, exports, or its normal browser UI.

Independently check the final three candidates, or all candidates if fewer, with a second provider when available. If unavailable, report single-provider evidence and the uncertainty. Never imply two interfaces backed by the same dataset are independent. Do not require repeated exhaustive research to finish a modest article.

Select one winner and explain the competitive opening, reader intent, original contribution, and limitations. A high volume or low difficulty badge is insufficient. If user thresholds are unmet, say so; do not silently lower them.

## Prepare the article

Read [editorial.md](references/editorial.md). If a writing sample exists, read it before drafting; later explicit corrections override habits in the sample.

Produce a coherent article answering the selected reader question early. Preserve the author's interpretation while distinguishing it from factual claims. Use verified sources; never invent personal experiences, research, numbers, or quotes. Source research is separate from keyword research.

Prepare the article, headline/subtitle, optional SEO title and description, up to five relevant topics, image direction/alt-text draft, and a short evidence summary together. Make headings and FAQs serve the reader; do not force a template into an essay. Preserve user edits when rereading the final file.

Run one integrated editorial pass followed by a whole-document factual and voice review. Rewrite affected paragraphs rather than repeatedly swapping phrases. Do not certify prose as human or mistake a clean word scan for editorial quality.

## Deliver or publish

Prepare mode ends with a reviewable article and metadata, evidence gaps, and a measurement plan. Use a task folder supplied by the user or a clearly named local output folder. Reuse existing artifacts instead of creating redundant reports.

When publication is explicitly requested, read [publishing.md](references/publishing.md). Use the live editor, preserve attribution and access settings, verify all publish controls, and confirm the public result. Subscriber email notification is a separate setting; do not infer permission from permission to publish.

Read [measurement.md](references/measurement.md) when defining outcomes or reporting results. Include a follow-up schedule in the deliverable; create actual scheduled jobs only when requested.

## Completion standard

- Evidence has source, date, market, and uncertainty; missing values stay unknown.
- Article fulfills the reader promise and preserves factual meaning and author voice.
- Metadata agrees with the article; references and image attribution survive editing.
- Prepare mode reports readiness and gaps. Publish mode reports the verified URL and observed access/notification state.
- Never promise rankings, conversion, earnings, or stars. Package validity and editorial scores are not outcome evidence.
