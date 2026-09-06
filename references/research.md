# Research protocol

## Evidence record

For each shortlisted keyword, retain exact query, target engine, country/market, language, provider and product/report, report URL or export/screenshot reference, retrieval time, volume period and method, metric-as-of date, SERP-as-of date, cache/refresh status, local or global volume value/band, organic difficulty with its scale and method when exposed, provider intent, observed SERP intent, trend, and missing-data reasons.

Provider search volumes and difficulty are estimates even when directly retrieved. Distinguish observed provider estimates, first-party measurements, user-supplied data, proxies, and editorial judgments.

Do not turn >10K into 10,000, sum overlapping queries into a traffic forecast, equate global volume with English demand, or treat Google Trends or Wikipedia attention as search volume. Search Console impressions are impressions for that property, not total market volume.

## Fast path

Start with existing relevant data. Reuse it only when query, engine, market, language, metric period, freshness, and purpose match. Retrieval time is not the data date. A 30-day cache is a convenience, not proof that volume, difficulty, or the SERP is current; refresh a finalist when stale data could change the choice.

Use this provider gate:

1. Read [provider-options.md](provider-options.md), verify its time-sensitive access claims against the linked first-party pages, and start with Semrush or another already accessible approved provider. Prefer existing access over new accounts or purchases. Accept a result only when provider provenance, target market, estimated monthly volume, and organic keyword difficulty are visible.
2. If Semrush's anonymous allowance is blocked or exhausted, check whether its current official terms offer more free usage after login. Tell the user what login unlocks and ask them to sign in or create the free account. Also tell them that a trial or paid plan is available, without starting or buying it for them.
3. If the user declines payment, declines the Semrush login, or Semrush still cannot provide complete metrics, move automatically to the next suitable free provider in [provider-options.md](provider-options.md). Ask before a new login or trial, and do not repeat a rejected payment prompt. Use the paid list only after free options or with the user's preference.
4. Gate each candidate separately. Every candidate eligible to win needs both metrics for the same target market and compatible period from a provider that exposes organic difficulty. Demand-only tools may supplement the record but cannot pass the gate. Rows missing either metric may be reported only as unvalidated leads.
5. If no free provider can validate the candidate set, present the current paid options once. If the user declines, stop before selecting a winning keyword, finalizing an SEO title, or drafting, revising, or publishing an SEO-led article. Prose-only and editorial-only work remains available only under the explicit exceptions in SKILL.md.

Check the host's tool inventory and current browser state before declaring a provider unavailable. If the user says a provider is logged in, attempt its normal interface through the available browser. A website login is valid UI access but does not imply API access. Never claim a free quota from memory: verify the current official terms. Do not install services, create accounts, start trials, subscribe, spend credits, or bypass access controls without the user's informed choice.

Accept an export only when it identifies the exact query, provider product/report, engine, country/database, volume scope, organic difficulty field, export date, and available metric/SERP freshness. Do not confuse paid-search competition with organic difficulty, global volume with national volume, or a transformed sheet with a first-party export. Reject invalid rows without discarding valid ones.

Ordinary web search remains supplemental. Use it after the metric gate for reader intent, competing formats, current results, and visible openings. It cannot replace the required volume and difficulty estimates.

Use bulk discovery and metrics where available. Shortlist by audience fit and intent before spending more calls. Inspect the strongest candidates rather than completing a large quota of seeds regardless of usefulness.

For finalists, triangulate with a second approved provider in comparable markets and periods when available. Provider difficulty scores are not interchangeable even when both use 0–100: apply a threshold only within the provider that defines it, retain methodology/version when exposed, and compare cross-provider difficulty as ordinal corroboration with the live SERP. Preserve discrepancies; investigate a greater-than-twofold volume difference or conflicting judgments when it could change selection. Never average the sources into artificial precision. Record known upstream-data overlap rather than calling vendor estimates statistically independent.

Inspect current organic results in the target locale using the intended engine, market, and language. Record provider-classified intent separately from observed SERP intent; when they differ or the results are mixed, the observed SERP controls format fit. Inspect page formats, dictionaries or brands distorting demand, established authorities, independent writers, Medium results, AI answers, snippets, and click-reducing features. Record device when the provider distinguishes it. Search APIs may omit features visible in a browser; do not claim to have inspected them.

Attainability needs a specific opening such as an underserved practical question or a dated result whose weakness the article can address credibly. Domain-wide Medium authority is not proof that a new author will rank. Medium [applies an internal threshold before stories enter external and native search indexes](https://help.medium.com/hc/en-us/articles/217991468-About-SEO-and-Medium); inspect a sample of the author or destination publication's recent eligible public stories when possible. Record account/publication context and separate SERP opportunity from Medium indexing eligibility. If indexing eligibility cannot be established, do not claim the article is likely to rank.

## Decision

Use an explained ordinal judgment, not a fabricated probability. Weigh attainability and engaged-reader fit first, followed by verified demand, original contribution, and durability. Preserve user-specified weights if supplied. Avoid an arbitrary arithmetic score that looks like a conversion forecast.

Return one winner, up to two alternatives, rejection reasons, and open evidence gaps. For the winner, retain a title decision record: exact target query, reader intent, proposed display title, optional search title, article promise, competitive opening, and why rejected titles weaken or change the opportunity. Separate facts from your interpretation.

Do not transfer demand or competition evidence to a materially different title merely because its topic is nearby. A wording change that preserves intent needs a clarity check; a change in intent, audience, or promised answer needs a focused research refresh. The stopping rule applies only after the candidate-level metric gate, evidence record, localized SERP inspection, and available second-provider triangulation are complete.
