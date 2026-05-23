# Children's Hospital of Philadelphia

Founded in 1855 as the first hospital in the United States dedicated to the healthcare of children, the Children's Hospital of Philadelphia (CHOP) is a 692-bed flagship pediatric academic medical center affiliated with the University of Pennsylvania Perelman School of Medicine. CHOP records roughly 1.63 million outpatient visits and 34,829 admissions per year and operates one of the largest pediatric research enterprises in the world through its Research Institute and the Center for Data Driven Discovery in Biomedicine (D3b).

From an API perspective, CHOP runs a production Epic-backed HL7 FHIR R4 endpoint at `https://epicnsproxy.chop.edu/fhir/api/FHIR/R4` exposing CMS-9115-F Patient Access and Provider Directory resources, US Core 6.1.0, SMART on FHIR, and HL7 Bulk Data. CHOP additionally publishes 320+ public repositories across the `chop-dbhi` (Department of Biomedical and Health Informatics) and `d3b-center` GitHub organizations, plus shared research data platforms including RADIANT, CAVATICA, PedcBioPortal, the Children's Brain Tumor Network, and the Kids First Data Resource Center.

## APIs

### CHOP FHIR R4 API
The CHOP FHIR Server is Epic (November 2025) on the back end, conforming to US Core 6.1.0 and the HL7 Bulk Data Access IG. Its CapabilityStatement advertises 59 FHIR resource types covering Patient Access (clinical + claims) and Provider Directory data per CMS-9115-F.

- Base URL: `https://epicnsproxy.chop.edu/fhir/api/FHIR/R4`
- CapabilityStatement: `https://epicnsproxy.chop.edu/fhir/api/FHIR/R4/metadata`
- SMART configuration: `https://epicnsproxy.chop.edu/fhir/api/FHIR/R4/.well-known/smart-configuration`
- Authorization: `https://epicnsproxy.chop.edu/fhir/oauth2/authorize`
- Token: `https://epicnsproxy.chop.edu/fhir/oauth2/token`
- App registration: [Epic on FHIR](https://fhir.epic.com) — select CHOP (Organization ID 332).
- Public landing: [CMS Interoperability and Patient Access](https://www.chop.edu/health-resources/cms-interoperability-and-patient-access)

### MyCHOP Patient Portal
MyChart-based patient portal for patients, parents, and guardians: virtual medical records, lab results, secure messaging, telehealth, refills, and scheduling. SMART apps approved via Epic on FHIR connect to the same underlying FHIR R4 surface.

- Portal: <https://mychop.chop.edu/MyChart/Authentication/Login>
- Overview: <https://www.chop.edu/mychop-patient-portal>

### Link2CHOP Referring Physician Portal
Internet-based portal for referring physician offices giving read-only access to the CHOP Epic EMR, plus the ability to place specialist consult orders for current CHOP patients.

- Portal: <https://link2chop.chop.edu>
- Overview: <https://www.chop.edu/healthcare-professionals/link2chop>

### D3b Data Sharing Platforms
The Center for Data Driven Discovery in Biomedicine (D3b) operates the open research infrastructure for pediatric cancer and rare disease. Programs include RADIANT (ARPA-H, up to $10M), CAVATICA, PedcBioPortal, the Children's Brain Tumor Network (CBTN), and the Gabriella Miller Kids First Data Resource Center.

- Site: <https://d3b.center>
- GitHub: <https://github.com/d3b-center> (153 public repos)

### DBHi Biomedical and Health Informatics
CHOP's Department of Biomedical and Health Informatics maintains 168 public repositories spanning health data infrastructure, EHR integration, and SMART on FHIR tools (prometheus-sql, sql-agent, dataexpress, dicom-anon, avocado, smart-asthma).

- Site: <http://dbhi.chop.edu>
- GitHub: <https://github.com/chop-dbhi> (168 public repos)

## Artifacts in this repository

| Folder | Files |
|---|---|
| `openapi/` | 1 OpenAPI 3.1 spec covering Patient Access + Provider Directory + Bulk Data |
| `json-schema/` | 4 JSON Schemas (Patient, Organization, Practitioner, Observation) |
| `json-ld/` | 1 JSON-LD context mapping FHIR + schema.org |
| `examples/` | 5 FHIR example payloads (Patient, Organization, Practitioner, Observation, Bulk export manifest) |
| `rules/` | 1 Spectral ruleset enforcing CHOP API conventions |
| `capabilities/` | 1 shared capability + 3 workflow capabilities (Patient Access, Provider Directory, Bulk Cohort Export) |
| `vocabulary/` | 1 controlled vocabulary covering CHOP, FHIR surface, and D3b programs |

## Notable absences

- CHOP does not publish a self-service developer portal with hosted API keys, public pricing, or rate-limit documentation — registration runs through Epic on FHIR and (for system-level use) custom agreements with CHOP IS&T.
- No AsyncAPI / event streaming spec is published.
- No public status page or changelog dedicated to the FHIR API.

## Maintainer

Kin Lane — [API Evangelist](https://apievangelist.com)
