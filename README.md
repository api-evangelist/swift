# SWIFT

SWIFT (Society for Worldwide Interbank Financial Telecommunication) is a global member-owned cooperative providing secure financial messaging services and reference data to financial institutions worldwide. SWIFT offers REST APIs for cross-border payment tracking (GPI), payment pre-validation, reference data lookup (SwiftRef), transaction screening, and instant payments. All APIs are documented using OpenAPI 3.0 and use OAuth 2.0 JWT-Bearer authentication.

- **Website:** https://www.swift.com
- **Developer Portal:** https://developer.swift.com
- **API Catalogue:** https://developer.swift.com/apis
- **Sandbox:** https://sandbox.swift.com

## APIs

### SwiftRef API
Real-time lookup and validation of payments reference data including BICs, IBANs, LEIs, National IDs, country codes, and currency codes. Enables financial institutions and fintechs to achieve higher straight-through processing rates.

- **Documentation:** https://developer.swift.com/apis/swiftref-api
- **Base URL:** https://api.swift.com/swiftrefdata
- **OpenAPI:** [openapi/swift-swiftref-api-openapi.yml](openapi/swift-swiftref-api-openapi.yml)

### SWIFT GPI API
Real-time cross-border payment tracking using UETR (Unique End-to-End Transaction Reference). Enables financial institutions to track, update statuses, and manage stop/recall requests for GPI payments.

- **Documentation:** https://developer.swift.com/apis/gpi-apis

### Payment Pre-validation API
Validates payment instructions before execution to reduce failures. Checks account numbers, BIC reachability, and beneficiary details.

- **Documentation:** https://developer.swift.com/apis/payment-pre-validation-api

## Artifacts

| Type | Path |
|---|---|
| OpenAPI Specs | [openapi/](openapi/) |
| Spectral Rules | [rules/swift-rules.yml](rules/swift-rules.yml) |
| Naftiko Capabilities | [capabilities/](capabilities/) |
| JSON Schema | [json-schema/](json-schema/) |
| JSON Structure | [json-structure/](json-structure/) |
| JSON-LD Context | [json-ld/swift-context.jsonld](json-ld/swift-context.jsonld) |
| Examples | [examples/](examples/) |
| Vocabulary | [vocabulary/swift-vocabulary.yml](vocabulary/swift-vocabulary.yml) |

## Naftiko Capabilities

### Shared Definitions
- [capabilities/shared/swift-swiftref.yaml](capabilities/shared/swift-swiftref.yaml) — SwiftRef reference data lookup consumer

### Workflow Capabilities
- [capabilities/payment-validation.yaml](capabilities/payment-validation.yaml) — Payment identifier validation workflow (SwiftRef, REST port 8080, MCP port 9090, 9 tools)

## Authentication

All SWIFT APIs use OAuth 2.0 with JWT-Bearer grant type (RFC 7523). Access requires SWIFT member credentials obtained from the SWIFT Developer Portal.

## Maintainers

- Kin Lane (kin@apievangelist.com)
