# Oracle Eloqua (oracle-eloqua)

Oracle Eloqua is a B2B marketing automation platform within Oracle Marketing Cloud that enables marketers to plan and execute multi-channel campaigns, manage leads, and personalize customer engagement across email, web, mobile, and social channels. The platform provides campaign design, lead scoring, segmentation, landing pages, and form processing for B2B demand generation teams. Oracle Eloqua exposes pod-specific REST APIs (Application API and Bulk API) authenticated via OAuth 2.0 or HTTP Basic Authentication, with base URLs resolved per-customer from the login.eloqua.com /id endpoint.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/oracle-eloqua/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/oracle-eloqua/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Marketing Automation
- B2B Marketing
- Email Marketing
- Campaign Management
- Lead Management
- Oracle

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Oracle Eloqua Application REST API

REST API for managing Eloqua marketing assets, contacts, accounts, campaigns, emails, forms, landing pages, and custom data objects. Base URL is pod-specific and resolved from the /id endpoint; supports OAuth 2.0 and HTTP Basic Authentication.

- **Human URL:** [https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/index.html](https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/index.html)
- **Base URL:** `https://secure.p01.eloqua.com/API/REST/2.0`

#### Tags

- Marketing Automation
- Campaigns
- Contacts
- Email Marketing

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/index.html)
- [Authentication](https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/Authentication_Auth.html)
- [Getting Started](https://docs.oracle.com/cloud/latest/marketingcs_gs/OMCAB/Developers/GettingStarted/Tutorials/determining-base-URLs.htm)
- [Postman Collection](collections/oracle-eloqua.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-eloqua.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Eloqua Bulk API

High-volume import/export REST API for moving large datasets of contacts, accounts, custom objects, and activities in and out of Eloqua. Uses the same OAuth 2.0 and HTTP Basic Authentication as the Application API.

- **Human URL:** [https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/index.html](https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/index.html)
- **Base URL:** `https://secure.p01.eloqua.com/API/Bulk/2.0`

#### Tags

- Bulk Data
- Data Import
- Data Export
- Marketing Automation

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/index.html)
- [Postman Collection](collections/oracle-eloqua.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-eloqua.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/oracle)
- [Website](https://www.oracle.com/cx/marketing/automation/)
- [Documentation](https://docs.oracle.com/en/cloud/saas/marketing/eloqua-develop/)
- [Pricing](https://www.oracle.com/cx/marketing/automation/)
- [Sign Up](https://login.eloqua.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
