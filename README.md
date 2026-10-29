# Children's Hospital of Philadelphia

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

Founded in 1855 as the first hospital in the United States dedicated to the healthcare of children, Children's Hospital of Philadelphia (CHOP) is a 692-bed flagship pediatric academic medical center affiliated with the University of Pennsylvania Perelman School of Medicine. CHOP records roughly 1.63 million outpatient visits and 34,829 admissions per year and operates one of the largest pediatric research enterprises in the world through its Research Institute and the Center for Data Driven Discovery in Biomedicine (D3b). From an API perspective, CHOP runs a production Epic-backed HL7 FHIR R4 endpoint at `https://epicnsproxy.chop.edu/fhir/api/FHIR/R4` exposing CMS-9115-F Patient Access and Provider Directory resources, US Core 6.1.0, SMART on FHIR, and HL7 Bulk Data. CHOP additionally publishes 320+ public repositories across the `chop-dbhi` (Department of Biomedical and Health Informatics) and `d3b-center` GitHub organizations, plus shared research data platforms including RADIANT, CAVATICA, PedcBioPortal, the Children's Brain Tumor Network, and the Kids First Data Resource Center.

**Areas:** Healthcare · Pediatrics · FHIR · SMART on FHIR · Patient Access · Provider Directory · CMS Interoperability · US Core · Bulk Data · Research Data · Open Data

## Children's Hospital of Philadelphia on APIs.io

Everything profiled for Children's Hospital of Philadelphia is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/childrens-hospital-of-philadelphia/](https://apis.io/providers/childrens-hospital-of-philadelphia/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [MyCHOP Patient Portal](https://apis.io/apis/childrens-hospital-of-philadelphia/mychop-patient-portal/) — MyChart-based patient portal that gives patients, parents and guardians access to virtual medical records, lab results, secure messaging, telehealth visits,…
- [Link2CHOP Referring Physician Portal](https://apis.io/apis/childrens-hospital-of-philadelphia/link2chop-referring-physician-portal/) — Internet-based portal for referring physician offices that provides real-time, read-only access to the CHOP Epic EMR. Surfaces discharge notes, operative…
- [D3b Data Sharing Platforms](https://apis.io/apis/childrens-hospital-of-philadelphia/d3b-data-sharing-platforms/) — The Center for Data Driven Discovery in Biomedicine (D3b) at CHOP operates the open research data infrastructure for pediatric cancer and rare disease.…
- [DBHi Biomedical and Health Informatics](https://apis.io/apis/childrens-hospital-of-philadelphia/dbhi-biomedical-and-health-informatics/) — CHOP's Department of Biomedical and Health Informatics (DBHi) maintains 168 public repositories covering health data infrastructure, EHR integration, and…
- [Children's Hospital of Philadelphia Bulk Data API](https://apis.io/apis/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-bulk-data-api/) — HL7 FHIR Bulk Data Access (Flat FHIR) Group-level export.
- [Children's Hospital of Philadelphia Patient Access API](https://apis.io/apis/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-patient-access-api/) — Patient-mediated clinical and claims data resources required under CMS-9115-F.
- [Children's Hospital of Philadelphia Provider Directory API](https://apis.io/apis/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-provider-directory-api/) — Public provider, organization, location, and endpoint resources required under CMS-9115-F.
- [Children's Hospital of Philadelphia SMART API](https://apis.io/apis/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-smart-api/) — SMART on FHIR launch and discovery endpoints.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Childrens Hospital Of Philadelphia Agentic Access](https://apis.io/agentic-access/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [CHOP FHIR Observation](https://apis.io/schemas/childrens-hospital-of-philadelphia/chop-fhir-observation/)
- [CHOP FHIR Organization](https://apis.io/schemas/childrens-hospital-of-philadelphia/chop-fhir-organization/)
- [CHOP FHIR Patient](https://apis.io/schemas/childrens-hospital-of-philadelphia/chop-fhir-patient/)
- [CHOP FHIR Practitioner](https://apis.io/schemas/childrens-hospital-of-philadelphia/chop-fhir-practitioner/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Childrens Hospital Of Philadelphia Context](https://apis.io/jsonld/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Children's Hospital of Philadelphia Vocabulary](https://apis.io/vocabularies/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Chop Fhir Bulk Export Example](https://apis.io/examples/childrens-hospital-of-philadelphia/chop-fhir-bulk-export-example/)
- [Chop Fhir Observation Example](https://apis.io/examples/childrens-hospital-of-philadelphia/chop-fhir-observation-example/)
- [Chop Fhir Organization Example](https://apis.io/examples/childrens-hospital-of-philadelphia/chop-fhir-organization-example/)
- [Chop Fhir Patient Example](https://apis.io/examples/childrens-hospital-of-philadelphia/chop-fhir-patient-example/)
- [Chop Fhir Practitioner Example](https://apis.io/examples/childrens-hospital-of-philadelphia/chop-fhir-practitioner-example/)

#### Collections (5)

Postman and Open Collection request collections.

- [Children's Hospital of Philadelphia FHIR R4 Bulk Data API](https://apis.io/collections/childrens-hospital-of-philadelphia/open-childrens-hospital-of-philadelphia-bulk-data-api/)
- [Children's Hospital of Philadelphia FHIR R4 Bulk Data Patient Access API](https://apis.io/collections/childrens-hospital-of-philadelphia/open-childrens-hospital-of-philadelphia-patient-access-api/)
- [Children's Hospital of Philadelphia FHIR R4 Bulk Data Provider Directory API](https://apis.io/collections/childrens-hospital-of-philadelphia/open-childrens-hospital-of-philadelphia-provider-directory-api/)
- [Children's Hospital of Philadelphia FHIR R4 Bulk Data SMART API](https://apis.io/collections/childrens-hospital-of-philadelphia/open-childrens-hospital-of-philadelphia-smart-api/)
- [Children's Hospital of Philadelphia FHIR R4 API](https://apis.io/collections/childrens-hospital-of-philadelphia/open-chop-fhir-r4/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Children's Hospital of Philadelphia — jsonschema rules](https://apis.io/rules/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-jsonschema-spectral-rules/)
- [Children's Hospital of Philadelphia — chop fhir rules](https://apis.io/rules/childrens-hospital-of-philadelphia/chop-fhir-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Childrens Hospital Of Philadelphia Authentication](https://apis.io/security/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-authentication/)
- [Childrens Hospital Of Philadelphia Domain Security](https://apis.io/security/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Childrens Hospital Of Philadelphia Scopes](https://apis.io/scopes/childrens-hospital-of-philadelphia/childrens-hospital-of-philadelphia-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.chop.edu/)
- [Support](https://www.chop.edu/contact-us)
- [Blog](https://www.chop.edu/news)
- [Compliance](https://www.chop.edu/health-resources/cms-interoperability-and-patient-access)
- [Terms of service](https://www.chop.edu/pages/terms-and-conditions)
- [Privacy policy](https://www.chop.edu/pages/privacy-policy)
- [GitHub](https://github.com/chop-dbhi)

## API Evangelist rating

**Kin Score 39.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 62.0 |
| Contract governance | 27.3 |
| Operational transparency | 2.6 |
| Developer ergonomics | 47.6 |
| Access clarity | 10.5 |

**Agent readiness 27.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 29.7** — Health

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/childrens-hospital-of-philadelphia/](https://apis.io/providers/childrens-hospital-of-philadelphia/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Children's Hospital of Philadelphia: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/childrens-hospital-of-philadelphia/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
