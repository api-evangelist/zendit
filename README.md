# Zendit (zendit)
Zendit is a cloud-based Prepay-as-a-Service platform that provides API access to a global prepaid ecosystem. The API enables businesses to offer mobile top-ups, data packages, digital gift cards, prepaid utility bill payments, and eSIM products through a single integration.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - eSIM, Gift Cards, Mobile Top-Up, Payments, Prepaid

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-03

## APIs

### Zendit API
The Zendit API provides programmatic access to the global prepaid ecosystem, enabling developers to offer mobile credit top-ups, data packages, digital gift cards, prepaid utility bill payments, and eSIM products. The platform supports self-onboarding, sandbox testing, and webhook notifications.

**Human URL:** [https://zendit.io/](https://zendit.io/)

#### Tags:

 - eSIM, Gift Cards, Mobile Top-Up, Prepaid

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/openapi/zendit-api.yml)
- [Documentation](https://zendit.io/)
- [APIReference](https://developers.zendit.io/api/)
- [GettingStarted](https://zendit.io/user-guide/getting-started/)
- [Authentication](https://developers.zendit.io/api/)
- [Guide](https://zendit.io/guide-to-integrating-zendits-api-into-your-projects/)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-schema/)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-structure/)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/json-ld/zendit-api-context.jsonld)
- [Example](https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/examples/)

## Common Properties

- [Website](https://zendit.io/)
- [Documentation](https://zendit.io/user-guide/)
- [GettingStarted](https://zendit.io/user-guide/getting-started/)
- [APIReference](https://developers.zendit.io/api/)
- [Login](https://console.zendit.io/login)
- [ChangeLog](https://zendit.io/zendit-new-features/)
- [GitHubOrganization](https://github.com/zenditplatform)
- [SpectralRules](https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/rules/zendit-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/vocabulary/zendit-vocabulary.yml)
- [NaftikoCapability](https://raw.githubusercontent.com/api-evangelist/zendit/refs/heads/main/capabilities/zendit-workflow.yaml)

## Features

| Name | Description |
|------|-------------|
| Mobile Top-Ups | Recharge prepaid mobile credit globally across thousands of carriers. |
| Data Bundles | Sell mobile data packages to subscribers worldwide. |
| eSIM Products | Offer eSIM plans for global travelers with QR-code activation. |
| Digital Gift Cards | Distribute prepaid gift cards across major brands. |
| Utility Bill Payments | Process prepaid utility payments for electricity, water, and gas. |
| Phone Number Lookup | Identify carrier from phone number in E.164 format. |
| Webhooks | Receive event notifications for transaction completions. |
| Async Reports | Generate transaction reports as CSV files asynchronously. |

## Use Cases

| Name | Description |
|------|-------------|
| Telecom Resellers | Power top-up and data plan sales for MVNOs and resellers. |
| Travel Apps | Embed eSIM purchases into travel booking flows. |
| Gift Card Marketplaces | Aggregate digital gift card inventory across brands. |
| Fintech Apps | Enable bill payment and prepaid services within wallets. |
| Loyalty Programs | Reward users with mobile top-ups, gift cards, or eSIM data. |

## Integrations

| Name | Description |
|------|-------------|
| Webhooks | Inbound webhook endpoints for transaction event notifications. |
| REST API | Bearer-token authenticated REST API over HTTPS. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [zendit-api.yml](openapi/zendit-api.yml)

### JSON Schema

- [zendit-api-balance-schema.json](json-schema/zendit-api-balance-schema.json)
- [zendit-api-brand-list-schema.json](json-schema/zendit-api-brand-list-schema.json)
- [zendit-api-brand-schema.json](json-schema/zendit-api-brand-schema.json)
- [zendit-api-esim-plan-list-schema.json](json-schema/zendit-api-esim-plan-list-schema.json)
- [zendit-api-esim-plan-schema.json](json-schema/zendit-api-esim-plan-schema.json)
- [zendit-api-esim-purchase-request-schema.json](json-schema/zendit-api-esim-purchase-request-schema.json)
- [zendit-api-offer-list-schema.json](json-schema/zendit-api-offer-list-schema.json)
- [zendit-api-offer-schema.json](json-schema/zendit-api-offer-schema.json)
- [zendit-api-phone-lookup-schema.json](json-schema/zendit-api-phone-lookup-schema.json)
- [zendit-api-price-schema.json](json-schema/zendit-api-price-schema.json)
- [zendit-api-purchase-list-schema.json](json-schema/zendit-api-purchase-list-schema.json)
- [zendit-api-purchase-schema.json](json-schema/zendit-api-purchase-schema.json)
- [zendit-api-redemption-instructions-schema.json](json-schema/zendit-api-redemption-instructions-schema.json)
- [zendit-api-refund-schema.json](json-schema/zendit-api-refund-schema.json)
- [zendit-api-report-request-schema.json](json-schema/zendit-api-report-request-schema.json)
- [zendit-api-report-schema.json](json-schema/zendit-api-report-schema.json)
- [zendit-api-topup-purchase-request-schema.json](json-schema/zendit-api-topup-purchase-request-schema.json)
- [zendit-api-transaction-list-schema.json](json-schema/zendit-api-transaction-list-schema.json)
- [zendit-api-transaction-schema.json](json-schema/zendit-api-transaction-schema.json)
- [zendit-api-voucher-purchase-request-schema.json](json-schema/zendit-api-voucher-purchase-request-schema.json)

### JSON Structure

- [zendit-api-balance-structure.json](json-structure/zendit-api-balance-structure.json)
- [zendit-api-brand-list-structure.json](json-structure/zendit-api-brand-list-structure.json)
- [zendit-api-brand-structure.json](json-structure/zendit-api-brand-structure.json)
- [zendit-api-esim-plan-list-structure.json](json-structure/zendit-api-esim-plan-list-structure.json)
- [zendit-api-esim-plan-structure.json](json-structure/zendit-api-esim-plan-structure.json)
- [zendit-api-esim-purchase-request-structure.json](json-structure/zendit-api-esim-purchase-request-structure.json)
- [zendit-api-offer-list-structure.json](json-structure/zendit-api-offer-list-structure.json)
- [zendit-api-offer-structure.json](json-structure/zendit-api-offer-structure.json)
- [zendit-api-phone-lookup-structure.json](json-structure/zendit-api-phone-lookup-structure.json)
- [zendit-api-price-structure.json](json-structure/zendit-api-price-structure.json)
- [zendit-api-purchase-list-structure.json](json-structure/zendit-api-purchase-list-structure.json)
- [zendit-api-purchase-structure.json](json-structure/zendit-api-purchase-structure.json)
- [zendit-api-redemption-instructions-structure.json](json-structure/zendit-api-redemption-instructions-structure.json)
- [zendit-api-refund-structure.json](json-structure/zendit-api-refund-structure.json)
- [zendit-api-report-request-structure.json](json-structure/zendit-api-report-request-structure.json)
- [zendit-api-report-structure.json](json-structure/zendit-api-report-structure.json)
- [zendit-api-topup-purchase-request-structure.json](json-structure/zendit-api-topup-purchase-request-structure.json)
- [zendit-api-transaction-list-structure.json](json-structure/zendit-api-transaction-list-structure.json)
- [zendit-api-transaction-structure.json](json-structure/zendit-api-transaction-structure.json)
- [zendit-api-voucher-purchase-request-structure.json](json-structure/zendit-api-voucher-purchase-request-structure.json)

### JSON-LD

- [zendit-api-context.jsonld](json-ld/zendit-api-context.jsonld)
- [zendit-api-esim-context.jsonld](json-ld/zendit-api-esim-context.jsonld)
- [zendit-api-topup-context.jsonld](json-ld/zendit-api-topup-context.jsonld)
- [zendit-api-voucher-context.jsonld](json-ld/zendit-api-voucher-context.jsonld)

### Examples

- [zendit-api-balance-example.json](examples/zendit-api-balance-example.json)
- [zendit-api-brand-example.json](examples/zendit-api-brand-example.json)
- [zendit-api-brand-list-example.json](examples/zendit-api-brand-list-example.json)
- [zendit-api-esim-plan-example.json](examples/zendit-api-esim-plan-example.json)
- [zendit-api-esim-plan-list-example.json](examples/zendit-api-esim-plan-list-example.json)
- [zendit-api-esim-purchase-request-example.json](examples/zendit-api-esim-purchase-request-example.json)
- [zendit-api-offer-example.json](examples/zendit-api-offer-example.json)
- [zendit-api-offer-list-example.json](examples/zendit-api-offer-list-example.json)
- [zendit-api-phone-lookup-example.json](examples/zendit-api-phone-lookup-example.json)
- [zendit-api-price-example.json](examples/zendit-api-price-example.json)
- [zendit-api-purchase-example.json](examples/zendit-api-purchase-example.json)
- [zendit-api-purchase-list-example.json](examples/zendit-api-purchase-list-example.json)
- [zendit-api-redemption-instructions-example.json](examples/zendit-api-redemption-instructions-example.json)
- [zendit-api-refund-example.json](examples/zendit-api-refund-example.json)
- [zendit-api-report-example.json](examples/zendit-api-report-example.json)
- [zendit-api-report-request-example.json](examples/zendit-api-report-request-example.json)
- [zendit-api-topup-purchase-request-example.json](examples/zendit-api-topup-purchase-request-example.json)
- [zendit-api-transaction-example.json](examples/zendit-api-transaction-example.json)
- [zendit-api-transaction-list-example.json](examples/zendit-api-transaction-list-example.json)
- [zendit-api-voucher-purchase-request-example.json](examples/zendit-api-voucher-purchase-request-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Zendit API](capabilities/shared/zendit-api.yaml) — 29 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Zendit Workflow](capabilities/zendit-workflow.yaml) | 1 | 20 | Developer |

## Vocabulary

- [Zendit Vocabulary](vocabulary/zendit-vocabulary.yml) — Unified taxonomy mapping 8 resources, 5 actions, 1 workflows, and 1 personas

## Rules

- [zendit-rules.yml](rules/zendit-rules.yml) — 18 rules enforcing Zendit API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
