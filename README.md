# Brennan Butler

Fullstack engineer at Hyperbound in San Francisco. I build AI agents and full-stack products, and I fix bugs in the open-source libraries I use.

## Open source

Most of my open source time goes to fixing real bugs I hit while building things. Some stuff that got merged recently:

- **[TanStack Query #11537](https://github.com/TanStack/query/pull/11537)** — cancelled retries were pausing the whole query pipeline.
- **[tRPC #7606](https://github.com/trpc/trpc/pull/7606)** — completed HTTP requests were holding onto their abort listeners.
- **[pg-boss #907](https://github.com/timgit/pg-boss/pull/907)** — shutdown could finish before workers that were already stopping.
- **[Oxc #26796](https://github.com/oxc-project/oxc/pull/26796)** — React Compiler fix for recursive function expressions, tested across ten React 19.2.3 scenarios.
- **[FastMCP #5181](https://github.com/PrefectHQ/fastmcp/pull/5181)** — binary resource contents were getting mangled in the response cache.
- **[EventSource #362](https://github.com/EventSource/eventsource/pull/362)** — messages kept dispatching after close.
- **[EventSource #363](https://github.com/EventSource/eventsource/pull/363)** — rejected response requests weren't aborted.
- **[rate-limit-redis #259](https://github.com/express-rate-limit/rate-limit-redis/pull/259)** — docs for the Redis command adapter signatures.
- **[enriched-markdown #833](https://github.com/software-mansion/enriched-markdown/pull/833)** — regression tests for multi-paragraph list markers on iOS.
- **[RecordSponge #1701](https://github.com/codeforpdx/recordexpungPDX/pull/1701)** — Code for PDX: added partners to the landing page and removed court fees.

[All authored pull requests](https://github.com/search?q=author%3Abrennanbutler01+is%3Apr&type=pullrequests) · [Open proposals](https://github.com/search?q=author%3Abrennanbutler01+is%3Apr+is%3Aopen&type=pullrequests)

Earlier this year I spent a few months in the [Vercel AI SDK](https://github.com/vercel/ai) issue tracker. I filed 272 detailed bug reports and got co-author credit on 56 commits that shipped to main. [All my AI SDK reports](https://github.com/vercel/ai/issues?q=is%3Aissue%20author%3Abrennanbutler01) · [Reports with fixes merged to main](https://github.com/vercel/ai/issues?q=is%3Aissue%20author%3Abrennanbutler01%20label%3Amerged-main)

A few of those fixes:

- [Cancelled tool calls no longer execute during repair](https://github.com/vercel/ai/commit/63175049119a46295e0ebffbcf638ef67c31f551)
- [`prepareStep` model choice now shows up in streamed results](https://github.com/vercel/ai/commit/669672843ced76ce4d49e0aa98f9c56b56463792)
- [Older `useObject` responses can't overwrite newer ones](https://github.com/vercel/ai/commit/a527dcd92d99cf53babb9edf38657a6fd459c294)
- [Final-step reasoning is exposed through stream result accessors](https://github.com/vercel/ai/commit/a7a66f553908ba54b40e24ff7d4b2edb7c06421c)

## Selected engineering work

**[Nombo](https://www.nombo.ai/) at Chestnut (YC P25).** Founding engineer. I set the technical direction through the company's product pivot and shipped an LLM-powered Mac and iPhone assistant (Electron + React Native/Expo). That meant agent memory and recovery, tool orchestration, structured output, SSE chat, scheduled and event-triggered workflows, human-in-the-loop approvals, evals, tracing, webhooks, billing, and the shared desktop/mobile contracts.

**Chestnut Mortgage.** Before the pivot I built the mortgage platform end to end, from product and system design through production. I turned the Fannie Mae Selling Guide into structured document rules wired to underwriting checks, grounded analysis, and a human final review, and built lender-pricing and follow-up workflows for portals that had no public APIs.

**State of Oregon.** A few engineering and QA roles: modernized C# and Oracle PL/SQL apps, chased down recurring application and database failures, and worked off a long-standing support backlog. At the Oregon Health Authority I led data modeling and source-to-target mapping for a migration; at Forestry and Human Services I built documentation, reporting, and training tools for nontechnical staff.

**[Alpaca Sho Pro](https://www.alpacashopro.com/).** A React/TypeScript/Node.js platform that real customers use — registration, class generation, scorecards, reporting, PayPal, all deployed on AWS.

## Current portfolio demos

Hosted demos running on synthetic or disposable data — no signup needed. Each source repo covers the implementation and its limits.

- **Case Reviews:** structured reviews, staff records, and PDF reports. [Frontend](https://github.com/brennanbutler01/case-reviews-portfolio) · [API](https://github.com/brennanbutler01/case-reviews-api) · [Demo](https://case-reviews-demo.vercel.app)
- **ODHS staff learning application:** courses, written-response review, and learner progress. [Source](https://github.com/brennanbutler01/tofu-tracker) · [Demo](https://tofu-tracker-demo.vercel.app)
- **Vietnamese vocabulary-learning application:** Vietnamese flashcards, spaced review, study history, and study groups. [Source](https://github.com/brennanbutler01/tofu-vocab) · [Demo](https://tofu-vocab-demo.vercel.app)
- **Tofu.Movies:** movie discovery, watchlists, watched status, reviews, and reactions. [Source](https://github.com/brennanbutler01/tofu-movies) · [Demo](https://tofu-movies-demo.vercel.app)
- **Tofu Jobs:** a React and TypeScript organizer backed by a C#/.NET and PostgreSQL API for companies, applications, interviews, activity notes, and cover-letter links. [Frontend](https://github.com/brennanbutler01/tofu-jobs) · [API](https://github.com/brennanbutler01/tofu-jobs-api) · [Demo](https://tofu-jobs-demo.vercel.app)
- **Học Việt API:** Go translation and vocabulary service with a read-only demo on personal Vercel hosting. [Source](https://github.com/brennanbutler01/hoc-viet) · [API docs](https://hoc-viet-demo.vercel.app/docs). Live translation is currently limited by the external provider.

## Earlier public work

- [Unity kart-racing project](https://github.com/brennanbutler01/SandboxMayhem) — an earlier C# and Unity class project.
- [Reelgood Scraper](https://github.com/brennanbutler01/reelgood-scraper) — an earlier public repository.

## Technologies

TypeScript, C#, Go, Python, SQL · React, Next.js, Electron, React Native/Expo · Node.js, .NET, GraphQL · PostgreSQL, Redis, BullMQ · Vercel AI SDK, model evaluations, Playwright · AWS, Vercel, Cloudflare, Terraform, Docker

## Let's connect

[LinkedIn](https://www.linkedin.com/in/brennanbutler1/) · [Email](mailto:brennanbutler01@gmail.com)
