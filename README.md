# Microsoft Azure Health Data Services

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

Microsoft Azure Health Data Services is a cloud-based suite of managed API services built on open healthcare standards — FHIR R4, DICOM, and HL7 — enabling healthcare organizations to collect, store, analyze, and exchange protected health information (PHI) at scale within a HIPAA/HITRUST compliance boundary.

## Services

- **FHIR Service** — Managed FHIR R4 REST API with SMART on FHIR v1/v2, RBAC, batch/transaction bundles, and advanced search.
- **DICOM Service** — DICOMweb API (STOW-RS, QIDO-RS, WADO-RS) for petabyte-scale medical imaging storage and exchange.
- **MedTech Service** — IoMT device data ingestion via Azure Event Hub, transforming device telemetry into FHIR Observation resources.
- **De-identification Service** — NLP-powered REST API to TAG, REDACT, or SURROGATE 27 PHI entity types in clinical text (HIPAA Safe Harbor and GDPR compliant).
- **Workspace Management API** — ARM control-plane API for provisioning and managing all workspace resources.

## Links

- [Product Page](https://azure.microsoft.com/en-us/products/health-data-services)
- [Documentation](https://learn.microsoft.com/en-us/azure/healthcare-apis/)
- [REST API Reference](https://learn.microsoft.com/en-us/rest/api/healthcareapis/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/health-data-services/)
- [GitHub (azure-rest-api-specs)](https://github.com/Azure/azure-rest-api-specs)
- [Release Notes](https://learn.microsoft.com/en-us/azure/healthcare-apis/release-notes-2024)

## APIs.json

This repository contains an [APIs.json 0.19](apis.yml) profile cataloging the Azure Health Data Services APIs for the [api-evangelist](https://github.com/api-evangelist) network.
