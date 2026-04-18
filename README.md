# Oracle E-Business Suite (oracle-e-business-suite)
A collection of APIs for Oracle E-Business Suite (EBS), Oracle's comprehensive suite of integrated, global business applications that supports today's evolving business models across financials, human capital management, supply chain, and manufacturing.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/oracle-e-business-suite/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consumer 
- **Access:** 3rd-Party 

## Tags:

 - Business Applications, E-Business Suite, Enterprise, ERP, Oracle

## Timestamps

- **Created:** 2024-01-01 
- **Modified:** 2026-04-18 

## APIs

### Oracle EBS Integrated SOA Gateway REST API
RESTful web services for Oracle E-Business Suite modules exposed through the Integrated SOA Gateway (ISG). PL/SQL APIs, Java Bean Services, Application Module Services, and other interface types from the Integration Repository can be deployed as lightweight REST services.

**Human URL:** [https://docs.oracle.com/cd/E26401_01/doc.122/e20927/T511473T516479.htm](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/T511473T516479.htm)

#### Tags:

 - Enterprise, Integration, Rest Services, Soa Gateway

#### Properties

- [OpenAPI](openapi/isg-rest-api.yml)
- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)

### Oracle EBS Financial Services API
APIs for financial management including General Ledger, Accounts Payable, Accounts Receivable, Fixed Assets, and Cash Management. These PL/SQL APIs are deployed as REST services through the Integrated SOA Gateway.

**Human URL:** [https://docs.oracle.com/cd/E26401_01/index.htm](https://docs.oracle.com/cd/E26401_01/index.htm)

#### Tags:

 - Accounting, Accounts Payable, Financials, General Ledger

#### Properties

- [OpenAPI](openapi/financial-services-api.yml)
- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)

### Oracle EBS Supply Chain Management API
APIs for inventory management, purchasing, order management, and logistics within Oracle E-Business Suite. Provides programmatic access to supply chain operations through PL/SQL interfaces deployable as REST services.

**Human URL:** [https://docs.oracle.com/cd/E26401_01/index.htm](https://docs.oracle.com/cd/E26401_01/index.htm)

#### Tags:

 - Inventory, Order Management, Purchasing, Supply Chain

#### Properties

- [OpenAPI](openapi/supply-chain-api.yml)
- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)

### Oracle EBS Human Resources API
APIs for human resources management, payroll processing, and workforce administration. Oracle HRMS provides PL/SQL packaged procedures and functions that serve as an open interface for managing employee data, compensation, and benefits.

**Human URL:** [https://docs.oracle.com/cd/E26401_01/nav/hcm.htm](https://docs.oracle.com/cd/E26401_01/nav/hcm.htm)

#### Tags:

 - Human Capital, Human Resources, Payroll, Workforce Management

#### Properties

- [OpenAPI](openapi/human-resources-api.yml)
- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)

### Oracle EBS Manufacturing API
APIs for discrete and process manufacturing operations including Bills of Material, Work in Process, and Work Orders. Provides programmatic access to manufacturing execution and planning functions.

**Human URL:** [https://docs.oracle.com/cd/E26401_01/index.htm](https://docs.oracle.com/cd/E26401_01/index.htm)

#### Tags:

 - Bills of Material, Manufacturing, Production, Work Orders

#### Properties

- [OpenAPI](openapi/manufacturing-api.yml)
- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)

### Oracle EBS e-Commerce Gateway API
Oracle e-Commerce Gateway provides EDI transaction support enabling Oracle E-Business Suite to exchange traditional Electronic Data Interchange documents with trading partners. Supports ASC X12 and EDIFACT standards.

**Human URL:** [https://docs.oracle.com/cd/E26401_01/doc.122/e20931/T168264T168267.htm](https://docs.oracle.com/cd/E26401_01/doc.122/e20931/T168264T168267.htm)

#### Tags:

 - Data Interchange, E-Commerce, Edi, Trading Partners

#### Properties

- [OpenAPI](openapi/ecommerce-gateway-api.yml)
- [Documentation](https://docs.oracle.com/cd/E26401_01/doc.122/e20931/T168264T168267.htm)

## Capabilities

Naftiko capability files organized by customer workflow with HTTP REST and MCP adapters.

### Shared Per-API Definitions (capabilities/shared/)

| File | API | Operations |
|---|---|---|
| [financial-services.yaml](capabilities/shared/financial-services.yaml) | Oracle EBS Financial Services | 11 |
| [supply-chain.yaml](capabilities/shared/supply-chain.yaml) | Oracle EBS Supply Chain | 11 |
| [human-resources.yaml](capabilities/shared/human-resources.yaml) | Oracle EBS Human Resources | 10 |
| [manufacturing.yaml](capabilities/shared/manufacturing.yaml) | Oracle EBS Manufacturing | 9 |
| [isg-rest.yaml](capabilities/shared/isg-rest.yaml) | Oracle EBS ISG REST | 5 |
| [ecommerce-gateway.yaml](capabilities/shared/ecommerce-gateway.yaml) | Oracle EBS e-Commerce Gateway | 7 |

### Workflow Capabilities

| File | Workflow | APIs Combined | Tools |
|---|---|---|---|
| [financial-operations.yaml](capabilities/financial-operations.yaml) | Financial Operations | Financial Services + Supply Chain | 17 |
| [workforce-management.yaml](capabilities/workforce-management.yaml) | Workforce Management | Human Resources | 10 |
| [manufacturing-operations.yaml](capabilities/manufacturing-operations.yaml) | Manufacturing Operations | Manufacturing + Supply Chain | 13 |
| [integration-and-edi.yaml](capabilities/integration-and-edi.yaml) | Integration and EDI | ISG REST + e-Commerce Gateway | 12 |

## Common Properties

- [Authentication](https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm)
- [Portal](https://developer.oracle.com/)
- [Documentation](https://docs.oracle.com/cd/E26401_01/index.htm)
- [GettingStarted](https://docs.oracle.com/cd/E26401_01/doc.122/e20925/T511175T513043.htm)
- [Support](https://support.oracle.com)
- [Blog](https://blogs.oracle.com/ebstech/)
- [ChangeLog](https://docs.oracle.com/cd/E26401_01/index.htm)
- [TermsOfService](https://www.oracle.com/legal/terms/)
- [PrivacyPolicy](https://www.oracle.com/legal/privacy/)
- [StatusPage](https://ocistatus.oraclecloud.com/)
- [SignUp](https://signup.cloud.oracle.com/)
- [Pricing](https://www.oracle.com/applications/ebusiness/)
- [GitHubOrganization](https://github.com/oracle)

## SDKs and Tools

- [Oracle OCI Java SDK](https://github.com/oracle/oci-java-sdk)
- [Oracle OCI Python SDK](https://github.com/oracle/oci-python-sdk)
- [Oracle OCI Go SDK](https://github.com/oracle/oci-go-sdk)
- [Oracle OCI .NET SDK](https://github.com/oracle/oci-dotnet-sdk)
- [Oracle OCI CLI](https://github.com/oracle/oci-cli)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
