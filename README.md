# KernelScan

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

KernelScan provides AI‑powered Linux kernel CVE intelligence, offering real‑time vulnerability analysis, VEX reports, and contextual risk assessments for kernel configurations. Users can upload .config files to receive CycloneDX VEX outputs, browse a searchable CVE database, and subscribe to daily digests. The platform includes free and paid tiers, with enterprise options for custom pricing and invoicing.

**Areas:** Security · Linux · CVE · AI · Vulnerability

## KernelScan on APIs.io

Everything profiled for KernelScan is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kernelscan-io/](https://apis.io/providers/kernelscan-io/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [KernelScan Analysis API](https://apis.io/apis/kernelscan-io/kernelscan-io-analysis-api/) — Submit a kernel .config and retrieve its CycloneDX VEX report.
- [KernelScan Auth API](https://apis.io/apis/kernelscan-io/kernelscan-io-auth-api/) — Registration, login, API keys, and account management.
- [KernelScan Billing API](https://apis.io/apis/kernelscan-io/kernelscan-io-billing-api/) — The billing API from KernelScan — 9 operation(s) for billing.
- [KernelScan Cve Candidates API](https://apis.io/apis/kernelscan-io/kernelscan-io-cve-candidates-api/) — Pre-CVE candidates: kernel fixes nominated for a CVE that is not published yet (Pro and Enterprise plans).
- [KernelScan Cves API](https://apis.io/apis/kernelscan-io/kernelscan-io-cves-api/) — Search and read Linux kernel CVEs.
- [KernelScan OAuth API](https://apis.io/apis/kernelscan-io/kernelscan-io-oauth-api/) — The oauth API from KernelScan — 5 operation(s) for oauth.
- [KernelScan Products API](https://apis.io/apis/kernelscan-io/kernelscan-io-products-api/) — The Products API from KernelScan — 6 operation(s) for products.
- [KernelScan Samples API](https://apis.io/apis/kernelscan-io/kernelscan-io-samples-api/) — Public sample / showcase analyses.
- [KernelScan Security Factors API](https://apis.io/apis/kernelscan-io/kernelscan-io-security-factors-api/) — Product security factors that contextualize CVE impact.
- [KernelScan Support API](https://apis.io/apis/kernelscan-io/kernelscan-io-support-api/) — Contact and feedback endpoints.
- [KernelScan Teams API](https://apis.io/apis/kernelscan-io/kernelscan-io-teams-api/) — The teams API from KernelScan — 4 operation(s) for teams.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [KernelScan Agentic Access](https://apis.io/agentic-access/kernelscan-io/kernelscan-io-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Body_analyze_api_analyze_post](https://apis.io/schemas/kernelscan-io/kernelscan-io-body-analyze-api-analyze-post/)
- [Body_upload_config_api_configs_uploads_post](https://apis.io/schemas/kernelscan-io/kernelscan-io-body-upload-config-api-configs-uploads-post/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Kernelscan Io Context](https://apis.io/jsonld/kernelscan-io/kernelscan-io-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [KernelScan API Rules](https://apis.io/rules/kernelscan-io/kernelscan-io-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [KernelScan Domain Security](https://apis.io/security/kernelscan-io/kernelscan-io-domain-security/)
- [KernelScan Vulnerability Disclosure](https://apis.io/security/kernelscan-io/kernelscan-io-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://kernelscan.io/)
- [Documentation](https://kernelscan.io/docs)
- [API reference](https://kernelscan.io/openapi.json)
- [Pricing](https://kernelscan.io/enterprise)
- [Changelog](https://github.com/kernelscan/kernelscan-dt-plugin/releases/latest)
- [Blog](https://kernelscan.io/blog)
- [Security](https://kernelscan.io/contact)
- [Terms of service](https://kernelscan.io/agb)
- [Privacy policy](https://kernelscan.io/privacy)
- [GitHub](https://github.com/kernelscan)

## API Evangelist rating

**Kin Score 45.6** — developing · rubric 0.27.0 · scored 2026-11-13

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 48.0 |
| Contract governance | 79.1 |
| Operational transparency | 31.6 |
| Developer ergonomics | 25.5 |
| Access clarity | 31.6 |

**Agent readiness 49.5** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 28.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kernelscan-io/](https://apis.io/providers/kernelscan-io/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for KernelScan: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kernelscan-io/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
