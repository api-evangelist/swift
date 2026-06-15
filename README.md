# SWIFT (swift)

SWIFT (Society for Worldwide Interbank Financial Telecommunication) is a global member-owned cooperative providing secure financial messaging services and reference data to financial institutions worldwide. SWIFT offers REST APIs for cross-border payment tracking (GPI), payment pre-validation, reference data lookup (SwiftRef), transaction screening, instant payments, and more. APIs use OAuth 2.0 authentication and are documented using OpenAPI 3.0.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Banking
- Cross-Border Payments
- Financial Messaging
- Financial Services
- GPI
- ISO 20022
- Payments

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-19

## APIs

### SwiftRef API

The SwiftRef API provides automated real-time lookup and validation of payments reference data including BICs, IBANs, LEIs, National IDs, country codes, and currency codes. Enables straight-through processing by validating financial identifiers before payment execution.

- **Human URL:** [https://developer.swift.com/apis/swiftref-api](https://developer.swift.com/apis/swiftref-api)
- **Base URL:** `https://api.swift.com/swiftrefdata`

#### Tags

- BIC Validation
- Financial Reference Data
- IBAN Validation
- LEI Validation
- Reference Data
- SwiftRef

#### Properties

- [Documentation](https://developer.swift.com/apis/swiftref-api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/openapi/swift-swiftref-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/swift-swiftref-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/swift-swiftref-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SWIFT GPI API

The SWIFT GPI (Global Payments Innovation) API enables financial institutions to track cross-border payment transactions in real time, update payment statuses, and manage stop-and-recall requests. Uses Unique End-to-End Transaction Reference (UETR) for tracking. Requires OAuth 2.0 authentication via JWT-Bearer grant type (RFC 7523).

- **Human URL:** [https://developer.swift.com/apis/gpi-apis](https://developer.swift.com/apis/gpi-apis)
- **Base URL:** `https://api.swift.com/swift-apigateway`

#### Tags

- Cross-Border Payments
- GPI
- ISO 20022
- Payment Tracking
- Payments
- UETR

#### Properties

- [Documentation](https://developer.swift.com/apis/gpi-apis)
- [Postman Collection](collections/swift-swiftref-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/swift-swiftref-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Payment Pre-validation API

The SWIFT Payment Pre-validation API allows financial institutions and PSPs to verify payment instruction data against reference data and counterparty information before executing a payment. Checks account numbers, country codes, routing information, and beneficiary account validity to reduce failed payments.

- **Human URL:** [https://developer.swift.com/apis/payment-pre-validation-api](https://developer.swift.com/apis/payment-pre-validation-api)

#### Tags

- Compliance
- Payment Pre-validation
- Payments
- Risk Management
- Straight-Through Processing

#### Properties

- [Documentation](https://developer.swift.com/apis/payment-pre-validation-api)
- [Product Page](https://www.swift.com/products/payment-pre-validation)
- [Postman Collection](collections/swift-swiftref-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/swift-swiftref-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Transaction Screening API

The SWIFT Transaction Screening API enables financial institutions to submit transactions to the SWIFT Transaction Screening Service (TSS) for sanctions and compliance screening before processing. Returns screening results with match details.

- **Human URL:** [https://developer.swift.com/](https://developer.swift.com/)

#### Tags

- AML
- Compliance
- Payments
- Sanctions Screening
- Transaction Screening

#### Properties

- [Postman Collection](collections/swift-swiftref-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/swift-swiftref-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.swift.com)
- [Developer Portal](https://developer.swift.com)
- [A P I Documentation](https://developer.swift.com/apis)
- [API Reference](https://developer.swift.com/reference)
- [GitHub Organization](https://github.com/swiftinc)
- [Sandbox](https://sandbox.swift.com)
- [Product Page](https://www.swift.com/products/swift-apis)
- [Support](https://www.swift.com/contact-us)
- [Terms of Service](https://developer.swift.com/terms)
- [Privacy Policy](https://www.swift.com/privacy-legal)
- [I S O20022](https://www.swift.com/standards/iso-20022)
- [Swift Ref](https://www.swift.com/products/swiftref)
- [G P I](https://www.swift.com/products/swift-gpi)
- [Postman Collection](https://www.postman.com/swift-developer-support/swift-api-sandbox-collections) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Login](https://developer.swift.com/login)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
