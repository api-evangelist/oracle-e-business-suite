# Oracle E-Business Suite (oracle-e-business-suite)

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

A collection of APIs for Oracle E-Business Suite (EBS), Oracle's comprehensive suite of integrated, global business applications that supports today's evolving business models across financials, human capital management, supply chain, and manufacturing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/oracle-e-business-suite/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/oracle-e-business-suite/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Business Applications
- E-Business Suite
- Enterprise
- ERP
- Oracle

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Oracle EBS Integrated SOA Gateway REST API

RESTful web services for Oracle E-Business Suite modules exposed through the Integrated SOA Gateway (ISG). PL/SQL APIs, Java Bean Services, Application Module Services, and other interface types from the Integration Repository can be deployed as lightweight REST services.

- **Human URL:** [https://docs.oracle.com/cd/E26401_01/doc.122/e20927/T511473T516479.htm](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/T511473T516479.htm)
- **Base URL:** `https://{instance}.oracle.com/webservices/rest/`

#### Tags

- Enterprise
- Integration
- Rest Services
- Soa Gateway

#### Properties

- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)
- [Getting Started](https://docs.oracle.com/cd/E26401_01/doc.122/e69284/T660136T660140.htm)
- [API Reference](https://docs.oracle.com/cd/E26401_01/doc.122/e20925/T511175T513043.htm)
- [OpenAPI](openapi/isg-rest-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/isg-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/isg-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Oracle EBS Integrated SOA Gateway SOAP Web Services

SOAP-based web services for Oracle E-Business Suite exposed through the Integrated SOA Gateway. Supports synchronous and asynchronous interaction patterns for PL/SQL APIs, Concurrent Programs, and Business Service Objects deployed to Oracle SOA Suite.

- **Human URL:** [https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)
- **Base URL:** `https://{instance}.oracle.com/webservices/SOAProvider/`

#### Tags

- Integration
- Soa Gateway
- Soap Services
- Web Services

#### Properties

- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)
- [API Reference](https://docs.oracle.com/cd/E26401_01/doc.122/e20923/T291171T291173.htm)
- [Getting Started](https://docs.oracle.com/cd/E26401_01/doc.122/e20925/T511175T513043.htm)
- [JSON Schema](json-schema/customer.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Postman Collection](collections/ecommerce-gateway-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ecommerce-gateway-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financial-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financial-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/human-resources-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/human-resources-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/isg-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/isg-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/manufacturing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/manufacturing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle EBS Financial Services API

APIs for financial management including General Ledger, Accounts Payable, Accounts Receivable, Fixed Assets, and Cash Management. These PL/SQL APIs can be deployed as REST or SOAP services through the Integrated SOA Gateway.

- **Human URL:** [https://docs.oracle.com/cd/E26401_01/index.htm](https://docs.oracle.com/cd/E26401_01/index.htm)
- **Base URL:** `https://{instance}.oracle.com/webservices/rest/`

#### Tags

- Accounting
- Accounts Payable
- Financials
- General Ledger

#### Properties

- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)
- [API Reference](https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm)
- [OpenAPI](openapi/financial-services-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/financial-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financial-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/invoice.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Oracle EBS Supply Chain Management API

APIs for inventory management, purchasing, order management, and logistics within Oracle E-Business Suite. Provides programmatic access to supply chain operations through PL/SQL interfaces deployable as REST services.

- **Human URL:** [https://docs.oracle.com/cd/E26401_01/index.htm](https://docs.oracle.com/cd/E26401_01/index.htm)
- **Base URL:** `https://{instance}.oracle.com/webservices/rest/`

#### Tags

- Inventory
- Order Management
- Purchasing
- Supply Chain

#### Properties

- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)
- [API Reference](https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm)
- [OpenAPI](openapi/supply-chain-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/supply-chain-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/purchase-order.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/supplier.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Oracle EBS Human Resources API

APIs for human resources management, payroll processing, and workforce administration. Oracle HRMS provides PL/SQL packaged procedures and functions that serve as an open interface for managing employee data, compensation, and benefits.

- **Human URL:** [https://docs.oracle.com/cd/E26401_01/nav/hcm.htm](https://docs.oracle.com/cd/E26401_01/nav/hcm.htm)
- **Base URL:** `https://{instance}.oracle.com/webservices/rest/`

#### Tags

- Human Capital
- Human Resources
- Payroll
- Workforce Management

#### Properties

- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)
- [API Reference](https://docs.oracle.com/cd/E26401_01/nav/hcm.htm)
- [OpenAPI](openapi/human-resources-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/human-resources-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/human-resources-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/employee.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Oracle EBS Manufacturing API

APIs for discrete and process manufacturing operations including Bills of Material, Work in Process, and Work Orders. Provides programmatic access to manufacturing execution and planning functions within Oracle E-Business Suite.

- **Human URL:** [https://docs.oracle.com/cd/E26401_01/index.htm](https://docs.oracle.com/cd/E26401_01/index.htm)
- **Base URL:** `https://{instance}.oracle.com/webservices/rest/`

#### Tags

- Bills of Material
- Manufacturing
- Production
- Work Orders

#### Properties

- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)
- [API Reference](https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm)
- [OpenAPI](openapi/manufacturing-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/manufacturing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/manufacturing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Oracle EBS e-Commerce Gateway API

Oracle e-Commerce Gateway provides EDI transaction support enabling Oracle E-Business Suite to exchange traditional Electronic Data Interchange documents with trading partners. Supports ASC X12 and EDIFACT standards through flat ASCII file integration with third-party EDI translators.

- **Human URL:** [https://docs.oracle.com/cd/E26401_01/doc.122/e20931/T168264T168267.htm](https://docs.oracle.com/cd/E26401_01/doc.122/e20931/T168264T168267.htm)
- **Base URL:** `https://{instance}.oracle.com/`

#### Tags

- Data Interchange
- E-Commerce
- Edi
- Trading Partners

#### Properties

- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20931/T168264T168267.htm)
- [OpenAPI](openapi/ecommerce-gateway-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ecommerce-gateway-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ecommerce-gateway-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Oracle EBS PL/SQL API Framework

The PL/SQL API framework provides the core programmatic interface to Oracle E-Business Suite database objects. These stored procedures and functions enable data manipulation across all EBS modules and can be published as REST services through the Integration Repository.

- **Human URL:** [https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm](https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm)
- **Base URL:** `https://{instance}.oracle.com/`

#### Tags

- Database Api
- Development Framework
- Pl/Sql
- Stored Procedures

#### Properties

- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm)
- [Getting Started](https://docs.oracle.com/cd/E26401_01/doc.122/e69284/T660136T660140.htm)
- [JSON Schema](json-schema/purchase-order.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/invoice.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/employee.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/customer.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/supplier.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Postman Collection](collections/ecommerce-gateway-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ecommerce-gateway-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/financial-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/financial-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/human-resources-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/human-resources-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/isg-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/isg-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/manufacturing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/manufacturing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/supply-chain-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supply-chain-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Authentication](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)
- [Portal](https://developer.oracle.com/)
- [Documentation](https://docs.oracle.com/cd/E26401_01/index.htm)
- [Getting Started](https://docs.oracle.com/cd/E26401_01/doc.122/e20925/T511175T513043.htm)
- [API Reference](https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm)
- [Support](https://support.oracle.com)
- [Blog](https://blogs.oracle.com/ebstech/)
- [Blog](https://blogs.oracle.com/ebs/)
- [Changelog](https://docs.oracle.com/cd/E26401_01/index.htm)
- [Terms of Service](https://www.oracle.com/legal/terms/)
- [Privacy Policy](https://www.oracle.com/legal/privacy/)
- [Status Page](https://ocistatus.oraclecloud.com/)
- [Sign Up](https://signup.cloud.oracle.com/)
- [Pricing](https://www.oracle.com/applications/ebusiness/)
- [GitHub Organization](https://github.com/oracle)
- [SDK](https://github.com/oracle/oci-java-sdk)
- [SDK](https://github.com/oracle/oci-python-sdk)
- [SDK](https://github.com/oracle/oci-go-sdk)
- [SDK](https://github.com/oracle/oci-dotnet-sdk)
- [C L I](https://github.com/oracle/oci-cli)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
