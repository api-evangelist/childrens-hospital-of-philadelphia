# Children's Hospital of Philadelphia (childrens-hospital-of-philadelphia)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Founded in 1855 as the first hospital in the United States dedicated to the healthcare of children, Children's Hospital of Philadelphia (CHOP) is a 692-bed flagship pediatric academic medical center affiliated with the University of Pennsylvania Perelman School of Medicine. CHOP records roughly 1.63 million outpatient visits and 34,829 admissions per year and operates one of the largest pediatric research enterprises in the world through its Research Institute and the Center for Data Driven Discovery in Biomedicine (D3b).

From an API perspective, CHOP runs a production Epic-backed HL7 FHIR R4 endpoint at `https://epicnsproxy.chop.edu/fhir/api/FHIR/R4` exposing CMS-9115-F Patient Access and Provider Directory resources, US Core 6.1.0, SMART on FHIR, and HL7 Bulk Data. CHOP additionally publishes 320+ public repositories across the `chop-dbhi` (Department of Biomedical and Health Informatics) and `d3b-center` GitHub organizations, plus shared research data platforms including RADIANT, CAVATICA, PedcBioPortal, the Children's Brain Tumor Network, and the Kids First Data Resource Center.

**APIs.json:** [https://github.com/api-evangelist/childrens-hospital-of-philadelphia](https://github.com/api-evangelist/childrens-hospital-of-philadelphia)

## Tags

- Healthcare
- Pediatrics
- FHIR
- SMART On FHIR
- Patient Access
- Provider Directory
- CMS Interoperability
- US Core
- Bulk Data
- Research Data
- Open Data

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### CHOP FHIR R4 API

The Children's Hospital of Philadelphia FHIR Server. Epic (November 2025) on the back end,
conforming to US Core 6.1.0 and the HL7 Bulk Data Access IG. Serves Patient Access (clinical + claims)
and Provider Directory data per CMS-9115-F, exposing 59 FHIR resource types including Patient,
AllergyIntolerance, Condition, Observation, MedicationRequest, Immunization, Procedure, Encounter,
DiagnosticReport, DocumentReference, Coverage, ExplanationOfBenefit, Claim, Practitioner,
PractitionerRole, Organization, Location, and Endpoint.

- **Human URL:** [https://www.chop.edu/health-resources/cms-interoperability-and-patient-access](https://www.chop.edu/health-resources/cms-interoperability-and-patient-access)
- **Base URL:** `https://epicnsproxy.chop.edu/fhir/api/FHIR/R4`

#### Tags

- FHIR
- SMART On FHIR
- Patient Access
- Provider Directory
- Bulk Data
- US Core

#### Properties

- [Documentation](https://www.chop.edu/health-resources/cms-interoperability-and-patient-access)
- [API Reference](https://epicnsproxy.chop.edu/fhir/api/FHIR/R4/metadata)
- [OpenAPI](openapi/chop-fhir-r4-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chop-fhir-r4.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chop-fhir-r4.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/chop-fhir-patient-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chop-fhir-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chop-fhir-practitioner-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chop-fhir-observation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/chop-fhir-patient-example.json)
- [Example](examples/chop-fhir-organization-example.json)
- [Example](examples/chop-fhir-practitioner-example.json)
- [Example](examples/chop-fhir-observation-example.json)
- [Example](examples/chop-fhir-bulk-export-example.json)
- [Authentication](https://epicnsproxy.chop.edu/fhir/oauth2/authorize)
- [Sandbox](https://fhir.epic.com/Documentation?docId=testpatients)

### MyCHOP Patient Portal

MyChart-based patient portal that gives patients, parents and guardians access to virtual medical
records, lab results, secure messaging, telehealth visits, medication refills, and appointment
scheduling. Supports multifactor authentication and multiple languages (Spanish, Arabic, Portuguese,
Chinese, and others). Apps approved via Epic on FHIR connect to the underlying CHOP FHIR R4 API.

- **Human URL:** [https://www.chop.edu/mychop-patient-portal](https://www.chop.edu/mychop-patient-portal)
- **Base URL:** `https://mychop.chop.edu/MyChart`

#### Tags

- Patient Portal
- MyChart
- Patient Access

#### Properties

- [Portal](https://mychop.chop.edu/MyChart/Authentication/Login)
- [Documentation](https://www.chop.edu/mychop-patient-portal)
- [Postman Collection](collections/chop-fhir-r4.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chop-fhir-r4.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Link2CHOP Referring Physician Portal

Internet-based portal for referring physician offices that provides real-time, read-only access to
the CHOP Epic EMR. Surfaces discharge notes, operative reports, progress notes, consult reports,
labs, imaging, medications, and diagnoses, plus the ability to place specialist consult orders for
current CHOP patients and to receive automated notifications for admissions, discharges, ED visits,
and scheduled appointments.

- **Human URL:** [https://www.chop.edu/healthcare-professionals/link2chop](https://www.chop.edu/healthcare-professionals/link2chop)
- **Base URL:** `https://link2chop.chop.edu`

#### Tags

- Referring Provider
- EMR Access
- Epic

#### Properties

- [Portal](https://link2chop.chop.edu)
- [Documentation](https://www.chop.edu/healthcare-professionals/link2chop)
- [Support](tel:+1-215-590-4357)
- [Postman Collection](collections/chop-fhir-r4.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chop-fhir-r4.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### D3b Data Sharing Platforms

The Center for Data Driven Discovery in Biomedicine (D3b) at CHOP operates the open research data
infrastructure for pediatric cancer and rare disease. Programs include RADIANT (Real-time Analysis
and Discovery in Integrated And Networked Technologies, an ARPA-H-funded cloud-based data sharing
and analytics platform up to $10 million), CAVATICA cloud computing platform, PedcBioPortal pediatric
cancer genomics portal, the Children's Brain Tumor Network (CBTN), and the Gabriella Miller Kids
First Data Resource Center. 153 public repositories on GitHub.

- **Human URL:** [https://d3b.center](https://d3b.center)

#### Tags

- Research Data
- Open Science
- Pediatric Cancer
- Bioinformatics

#### Properties

- [Documentation](https://d3b.center)
- [GitHub Organization](https://github.com/d3b-center)
- [GitHub Repository](https://github.com/d3b-center/OpenPedCan-analysis)
- [GitHub Repository](https://github.com/d3b-center/annoFuse)
- [GitHub Repository](https://github.com/d3b-center/bixtools)
- [GitHub Repository](https://github.com/d3b-center/peds-brain-auto-seg-public)
- [GitHub Repository](https://github.com/d3b-center/D3b-RADIANT-Annotation)
- [Postman Collection](collections/chop-fhir-r4.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chop-fhir-r4.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DBHi Biomedical and Health Informatics

CHOP's Department of Biomedical and Health Informatics (DBHi) maintains 168 public repositories
covering health data infrastructure, EHR integration, and SMART on FHIR tools. Notable open-source
projects include prometheus-sql, sql-agent, dataexpress (cross-database ETL), dicom-anon (DICOM
anonymizer), avocado (metadata APIs for Django), origins (bi-temporal database), data-models
(biomedical data models), smart-asthma, ecease-smart-app, and dr-trace.

- **Human URL:** [http://dbhi.chop.edu](http://dbhi.chop.edu)

#### Tags

- Health Informatics
- Open Source
- SMART On FHIR

#### Properties

- [GitHub Organization](https://github.com/chop-dbhi)
- [GitHub Repository](https://github.com/chop-dbhi/prometheus-sql)
- [GitHub Repository](https://github.com/chop-dbhi/sql-agent)
- [GitHub Repository](https://github.com/chop-dbhi/dataexpress)
- [GitHub Repository](https://github.com/chop-dbhi/dicom-anon)
- [GitHub Repository](https://github.com/chop-dbhi/smart-asthma)
- [GitHub Repository](https://github.com/chop-dbhi/avocado)
- [Postman Collection](collections/chop-fhir-r4.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chop-fhir-r4.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.chop.edu)
- [Developer Portal](https://fhir.epic.com)
- [GitHub Organization](https://github.com/chop-dbhi)
- [GitHub Organization](https://github.com/d3b-center)
- [Blog](https://www.chop.edu/news)
- [Privacy Policy](https://www.chop.edu/pages/privacy-policy)
- [Terms of Service](https://www.chop.edu/pages/terms-and-conditions)
- [Compliance](https://www.chop.edu/health-resources/cms-interoperability-and-patient-access)
- [Support](https://www.chop.edu/contact-us)
- [Spectral Rules](rules/chop-fhir-rules.yml)
- [JSON-LD](json-ld/childrens-hospital-of-philadelphia-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/childrens-hospital-of-philadelphia-vocabulary.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
