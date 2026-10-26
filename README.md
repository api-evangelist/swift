# SWIFT (swift)

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
