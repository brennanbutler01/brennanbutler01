# Brennan Butler

Fullstack Engineer at Hyperbound, based in San Francisco. I build production AI agents and full-stack products, and contribute to the Vercel AI SDK with co-author credit on merged fixes across its runtime, providers, and React APIs.

## Open source

I contribute to the [Vercel AI SDK](https://github.com/vercel/ai) through bug investigation, runnable reproductions, source-level diagnosis, and focused fix proposals. As of October 11, 2026, my contributions have led to 49 fixes merged to main, with co-author credit on all 49 fix commits. I have submitted 202 bug reports and improvement proposals; 165 carry the project's successful-reproduction label.

This follows the SDK's [issue-first contribution process](https://github.com/vercel/ai/blob/main/CONTRIBUTING.md): maintainers and automated workflows prepare fixes from detailed reports and credit contributors on the resulting commits. My work covers streaming, cancellation, tool execution, structured output, provider adapters, and client state.

Selected merged fixes with co-author credit:

- [Cancellation during tool-call repair](https://github.com/vercel/ai/commit/63175049119a46295e0ebffbcf638ef67c31f551): prevent repaired tools from executing after cancellation.
- [Model-switching metadata](https://github.com/vercel/ai/commit/669672843ced76ce4d49e0aa98f9c56b56463792): report the model selected by `prepareStep` in streamed results and callbacks.
- [Overlapping React requests](https://github.com/vercel/ai/commit/a527dcd92d99cf53babb9edf38657a6fd459c294): prevent older `useObject` responses from overwriting newer results.

[All my AI SDK reports](https://github.com/vercel/ai/issues?q=is%3Aissue%20author%3Abrennanbutler01) · [Reports with fixes merged to main](https://github.com/vercel/ai/issues?q=is%3Aissue%20author%3Abrennanbutler01%20label%3Amerged-main)

I also authored eight merged pull requests across six other libraries and Code for PDX's RecordSponge project, verified October 11, 2026:

- **[pg-boss #907](https://github.com/timgit/pg-boss/pull/907):** merged a fix so shutdown waits for workers that are already stopping.
- **[Oxc #26796](https://github.com/oxc-project/oxc/pull/26796):** merged a React Compiler fix for recursive function expressions, verified with ten React 19.2.3 runtime scenarios.
- **[RecordSponge #1701](https://github.com/codeforpdx/recordexpungPDX/pull/1701):** merged a Code for PDX change adding partners to the landing page and removing court fees.
- **[FastMCP #5181](https://github.com/PrefectHQ/fastmcp/pull/5181):** merged a fix that preserves binary resource contents in the response cache.
- **[EventSource #362](https://github.com/EventSource/eventsource/pull/362):** merged a fix that stops dispatching messages after close.
- **[EventSource #363](https://github.com/EventSource/eventsource/pull/363):** merged a fix that aborts rejected response requests.
- **[rate-limit-redis #259](https://github.com/express-rate-limit/rate-limit-redis/pull/259):** merged documentation clarifying Redis command adapter signatures.
- **[enriched-markdown #833](https://github.com/software-mansion/enriched-markdown/pull/833):** merged iOS regression coverage for multi-paragraph list markers.

[All authored pull requests](https://github.com/search?q=author%3Abrennanbutler01+is%3Apr&type=pullrequests) · [Open proposals](https://github.com/search?q=author%3Abrennanbutler01+is%3Apr+is%3Aopen&type=pullrequests)

## Selected engineering work

**[Nombo](https://www.nombo.ai/) at Chestnut (YC P25).** As Founding Software Engineer, I set technical direction through the company's product pivot and shipped an LLM-powered Mac and iPhone assistant with Electron and React Native/Expo. My work spans agent memory and recovery, tool orchestration, structured output, Server-Sent Events (SSE) chat, scheduled and event-triggered workflows, human-in-the-loop approvals, model evaluations, tracing, webhooks, billing, and shared desktop/mobile contracts.

**Chestnut Mortgage.** Before the pivot, I built the mortgage platform from product and system design through production. I converted the Fannie Mae Selling Guide into structured document-type rules and connected borrower documents to underwriting checks, grounded analysis, and human final review. I also built lender-pricing and follow-up workflows for portals without public APIs.

**State of Oregon.** Across engineering and quality roles, I modernized C# and Oracle PL/SQL applications, resolved recurring application and database failures, and reduced a longstanding support backlog. At the Oregon Health Authority, I led data modeling and source-to-target mapping for a migration. At Forestry and Human Services, I built documentation, reporting, and staff-training tools with nontechnical users.

**[Alpaca Sho Pro](https://www.alpacashopro.com/).** Built a customer-used React, TypeScript, and Node.js platform for registration, class generation, scorecards, reporting, PayPal workflows, and AWS deployment.

## Current portfolio demos

These hosted demos use synthetic or disposable data and do not require signup. Each source repository documents its implementation and limitations.

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
