# Microsoft Azure Health Data Services

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
