# Snapvisor

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Snapvisor provides visual regression testing and review workflow for web applications. It captures screenshots of pages, detects visual changes, and lets teams approve or reject updates via pull‑request status checks. Snapvisor integrates with CI/CD tools like GitHub, GitLab, Playwright, Cypress, Storybook, and Puppeteer, offering self‑hosting options, role‑based access, SSO/SAML, and usage‑based pricing. The platform is built on an open‑source engine and includes an MCP server for AI agents to create builds and run visual diffs.

**Areas:** Visual Regression · CI/CD · Open Source · SaaS · AI Integration

## Snapvisor on APIs.io

Everything profiled for Snapvisor is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/snapvisor-io/](https://apis.io/providers/snapvisor-io/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [Snapvisor Analytics API](https://apis.io/apis/snapvisor-io/snapvisor-io-analytics-api/) — Retrieve account-level build and screenshot metrics over time.
- [Snapvisor Authentication API](https://apis.io/apis/snapvisor-io/snapvisor-io-authentication-api/) — Exchange CI and CLI credentials for a Snapvisor project token. Use these endpoints to obtain the bearer token that authenticates every other request.
- [Snapvisor Automations API](https://apis.io/apis/snapvisor-io/snapvisor-io-automations-api/) — Run actions when a build event matches your conditions — post to Slack, Microsoft Teams or Discord when a build completes or is reviewed.
- [Snapvisor Billing API](https://apis.io/apis/snapvisor-io/snapvisor-io-billing-api/) — Read a team's plan and usage, list plans, and start an upgrade, a cancellation or a spend limit change. Payment pages open through single-use links.
- [Snapvisor Builds API](https://apis.io/apis/snapvisor-io/snapvisor-io-builds-api/) — Create, finalize, update, and inspect visual testing builds, including their screenshot diffs. This is the core of the visual testing workflow.
- [Snapvisor Comments API](https://apis.io/apis/snapvisor-io/snapvisor-io-comments-api/) — Collaborate on builds with threaded comments: post and edit comments, react with emojis, resolve threads, and manage notification subscriptions.
- [Snapvisor Deployments API](https://apis.io/apis/snapvisor-io/snapvisor-io-deployments-api/) — Create, finalize, and resolve deployments to publish and serve project artifacts.
- [Snapvisor Free tools API](https://apis.io/apis/snapvisor-io/snapvisor-io-free-tools-api/) — Free endpoints with no key: compare two images with the same diff engine every build uses. Limited per address; see each operation.
- [Snapvisor Integrations API](https://apis.io/apis/snapvisor-io/snapvisor-io-integrations-api/) — List, connect, check and disconnect the services an account uses: GitHub, GitLab, Cursor Origin, Slack, Discord, Microsoft Teams, and your own sign-in…
- [Snapvisor Media API](https://apis.io/apis/snapvisor-io/snapvisor-io-media-api/) — Upload standalone images and videos, with no build or test run behind them, and get back a shareable URL plus ready-to-paste Markdown. Built for embedding a…
- [Snapvisor Members API](https://apis.io/apis/snapvisor-io/snapvisor-io-members-api/) — Manage who is on a team and what they can reach: list members, change their role, remove them, and send or cancel invitations.
- [Snapvisor Projects API](https://apis.io/apis/snapvisor-io/snapvisor-io-projects-api/) — Retrieve project metadata, either by slug or for the project tied to the current token.
- [Snapvisor Repos API](https://apis.io/apis/snapvisor-io/snapvisor-io-repos-api/) — The Repos API from Snapvisor — 1 operation(s) for repos.
- [Snapvisor Reviews API](https://apis.io/apis/snapvisor-io/snapvisor-io-reviews-api/) — Submit, list, and dismiss reviews to approve or reject the changes captured in a build.
- [Snapvisor Support API](https://apis.io/apis/snapvisor-io/snapvisor-io-support-api/) — Send a request to the support team and list the requests you sent. Replies arrive by email.
- [Snapvisor Teams API](https://apis.io/apis/snapvisor-io/snapvisor-io-teams-api/) — The Teams API from Snapvisor — 3 operation(s) for teams.
- [Snapvisor Tests API](https://apis.io/apis/snapvisor-io/snapvisor-io-tests-api/) — Inspect a test's flakiness — how often it changed and how erratically — list the changes that keep coming back, and ignore the ones that are only noise.
- [Snapvisor Users API](https://apis.io/apis/snapvisor-io/snapvisor-io-users-api/) — Retrieve information about the user authenticated by the current personal access token.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Snapvisor Agentic Access](https://apis.io/agentic-access/snapvisor-io/snapvisor-io-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [AccountAnalytics](https://apis.io/schemas/snapvisor-io/snapvisor-io-account-analytics/)
- [BillingStatus](https://apis.io/schemas/snapvisor-io/snapvisor-io-billing-status/)
- [Build](https://apis.io/schemas/snapvisor-io/snapvisor-io-build/)
- [Media](https://apis.io/schemas/snapvisor-io/snapvisor-io-media/)
- [ScreenshotInput](https://apis.io/schemas/snapvisor-io/snapvisor-io-screenshot-input/)
- [SnapshotDiff](https://apis.io/schemas/snapvisor-io/snapvisor-io-snapshot-diff/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Snapvisor Io Context](https://apis.io/jsonld/snapvisor-io/snapvisor-io-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Snapvisor API Rules](https://apis.io/rules/snapvisor-io/snapvisor-io-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Snapvisor Authentication](https://apis.io/security/snapvisor-io/snapvisor-io-authentication/)
- [Snapvisor Domain Security](https://apis.io/security/snapvisor-io/snapvisor-io-domain-security/)
- [Snapvisor Vulnerability Disclosure](https://apis.io/security/snapvisor-io/snapvisor-io-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Snapvisor Scopes](https://apis.io/scopes/snapvisor-io/snapvisor-io-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Snapvisor Plans Pricing](https://apis.io/plans/snapvisor-io/snapvisor-io-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://snapvisor.io/)
- [Documentation](https://snapvisor.io/docs)
- [Getting started](https://snapvisor.io/docs/getting-started)
- [API reference](https://snapvisor.io/docs/api-reference)
- [Pricing](https://snapvisor.io/docs/pricing)
- [Sign up](https://app.snapvisor.io/signup)
- [Support](https://snapvisor.io/docs/team-members-and-roles)
- [Terms of service](https://snapvisor.io/terms)
- [Privacy policy](https://snapvisor.io/privacy)
- [Status](https://status.snapvisor.io/)

## API Evangelist rating

**Kin Score 66.9** — exemplar · rubric 0.27.0 · scored 2026-11-25

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 62.9 |
| Contract governance | 79.1 |
| Operational transparency | 26.3 |
| Developer ergonomics | 66.0 |
| Access clarity | 73.2 |

**Agent readiness 62.5** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 40.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/snapvisor-io/](https://apis.io/providers/snapvisor-io/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Snapvisor: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/snapvisor-io/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
