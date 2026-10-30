# Neuphonic

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

Neuphonic is an ultra-low-latency voice AI platform specializing in real-time text-to-speech synthesis with sub-25ms latency, making it suitable for conversational AI and live applications. The platform provides both a cloud-hosted API with WebSocket streaming and Server-Sent Events (SSE), as well as open-source on-device models (NeuTTS Air, NeuTTS Nano) that run without a GPU. Neuphonic supports nine languages including English, Spanish, German, French, Urdu, Japanese, Korean, Chinese, and Portuguese, and offers instant voice cloning from short audio samples. Developers can also build conversational AI agents via the Agent API, which integrates with GPT-4o and supports Model Context Protocol (MCP) servers. Authentication uses API keys passed via the X-API-KEY header for SSE and as a query parameter for WebSocket connections.

**Areas:** Text-to-Speech · Voice AI · Audio · Streaming · WebSocket · Voice Cloning · Conversational AI · Real-Time · Multilingual · On-Device AI

## Neuphonic on APIs.io

Everything profiled for Neuphonic is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/neuphonic/](https://apis.io/providers/neuphonic/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Neuphonic TTS WebSocket API](https://apis.io/apis/neuphonic/neuphonic-tts-websocket-api/) — WebSocket endpoint for continuous, low-latency text-to-speech streaming. Enables real-time voice synthesis with sub-25ms latency, supporting multiple text…
- [Neuphonic Voice Cloning API](https://apis.io/apis/neuphonic/neuphonic-voice-cloning-api/) — REST API for creating and managing cloned voices. Accepts audio samples (MP3 or WAV, minimum 6 seconds, under 10MB) and generates a custom voice model.…
- [Neuphonic Agent API](https://apis.io/apis/neuphonic/neuphonic-agent-api/) — REST API for creating and managing conversational AI voice agents. Agents combine Neuphonic TTS with GPT-4o for interactive voice applications and support…
- [Neuphonic Agents API](https://apis.io/apis/neuphonic/neuphonic-agents-api/) — The Agents API from Neuphonic — 3 operation(s) for agents.
- [Neuphonic Ping API](https://apis.io/apis/neuphonic/neuphonic-ping-api/) — The Ping API from Neuphonic — 1 operation(s) for ping.
- [Neuphonic Sse API](https://apis.io/apis/neuphonic/neuphonic-sse-api/) — The Sse API from Neuphonic — 2 operation(s) for sse.
- [Neuphonic Voices API](https://apis.io/apis/neuphonic/neuphonic-voices-api/) — The Voices API from Neuphonic — 2 operation(s) for voices.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Neuphonic Agentic Access](https://apis.io/agentic-access/neuphonic/neuphonic-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Agent](https://apis.io/schemas/neuphonic/neuphonic-agent/)
- [SSE TTS Request](https://apis.io/schemas/neuphonic/neuphonic-sse-request/)
- [Voice](https://apis.io/schemas/neuphonic/neuphonic-voice/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Neuphonic Context](https://apis.io/jsonld/neuphonic/neuphonic-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Neuphonic Vocabulary](https://apis.io/vocabularies/neuphonic/neuphonic-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Clone Voice](https://apis.io/examples/neuphonic/clone-voice/)
- [Create Agent](https://apis.io/examples/neuphonic/create-agent/)
- [List Voices](https://apis.io/examples/neuphonic/list-voices/)
- [Sse Speak](https://apis.io/examples/neuphonic/sse-speak/)

#### Collections (4)

Postman and Open Collection request collections.

- [Neuphonic Agents API](https://apis.io/collections/neuphonic/open-neuphonic-agents-api/)
- [Neuphonic Agents Ping API](https://apis.io/collections/neuphonic/open-neuphonic-ping-api/)
- [Neuphonic Agents Sse API](https://apis.io/collections/neuphonic/open-neuphonic-sse-api/)
- [Neuphonic Agents Voices API](https://apis.io/collections/neuphonic/open-neuphonic-voices-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Neuphonic — jsonschema rules](https://apis.io/rules/neuphonic/neuphonic-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Neuphonic Authentication](https://apis.io/security/neuphonic/neuphonic-authentication/)
- [Neuphonic Domain Security](https://apis.io/security/neuphonic/neuphonic-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Neuphonic Plans Pricing](https://apis.io/plans/neuphonic/neuphonic-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Neuphonic Rate Limits](https://apis.io/rate-limits/neuphonic/neuphonic-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Neuphonic Finops](https://apis.io/finops/neuphonic/neuphonic-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.neuphonic.com/)
- [Documentation](https://docs.neuphonic.com/)
- [Blog](https://www.neuphonic.com/blog)
- [GitHub](https://github.com/neuphonic)
- [Status](https://status.neuphonic.com/)

## API Evangelist rating

**Kin Score 35.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 66.8 |
| Contract governance | 23.5 |
| Operational transparency | 26.3 |
| Developer ergonomics | 27.4 |
| Access clarity | 7.9 |

**Agent readiness 21.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.0** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/neuphonic/](https://apis.io/providers/neuphonic/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Neuphonic: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/neuphonic/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
