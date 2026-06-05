# Children's Hospital of Philadelphia (childrens-hospital-of-philadelphia)

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
