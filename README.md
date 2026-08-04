# Fawry (fawry)

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

Fawry is Cairo-based Egypt's leading provider of e-payments and digital finance solutions, operating a nationwide network for card, e-wallet, and cash-based bill, merchant, government, and education payments. The FawryPay acceptance platform exposes a server-to-server REST API plus native Android, iOS, Flutter, and React Native SDKs and certified plugins for Magento, Shopify, and WooCommerce that let merchants charge cards (including 3DS), e-wallets, ValU, and bank installments, generate FawryPay reference numbers payable across more than 250,000 Fawry POS locations and partner channels, issue refunds, cancel unpaid orders, and reconcile via signed server notifications. Fawry also offers consumer products (myfawry super app, yellowcard prepaid card, FawryPlus, TicketsMall), enterprise and SME acceptance, pay-out, micro-finance, and consumer-finance services. Fawry is publicly listed on the Egyptian Exchange as FWRY.CA.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fawry/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fawry/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Payments
- E-Payments
- Digital Finance
- Fintech
- Egypt
- Cards
- Wallets
- Bill Payments
- POS
- Micro-Finance
- Installments
- 3D Secure
- Refunds
- Webhooks
- Mobile SDK
- E-Commerce Plugins
- Magento
- Shopify
- WooCommerce

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### FawryPay Server API

Server-to-server REST API for creating FawryPay charges (card, 3DS, e-wallet, ValU, bank installments, PayAtFawry reference numbers), issuing refunds, cancelling unpaid orders, querying payment status, and listing bank installment plans. Authenticated per request via a merchant code and SHA-256 signature over the request body and a shared secureKey.

- **Human URL:** [https://developer.fawrystaging.com/docs/server-apis/server-apis-overview](https://developer.fawrystaging.com/docs/server-apis/server-apis-overview)

#### Tags

- Payments
- Refunds
- Installments
- E-Commerce

#### Properties

- [Documentation](https://developer.fawrystaging.com/docs/server-apis/server-apis-overview)
- [Documentation](https://developer.fawrystaging.com/docs/server-apis/create-payment-refno-apis)
- [Documentation](https://developer.fawrystaging.com/docs/server-apis/refund-issue-api)
- [Documentation](https://developer.fawrystaging.com/docs/server-apis/cancel-payment-api)
- [Documentation](https://developer.fawrystaging.com/docs/server-apis/auth-capture-payment-apis)
- [OpenAPI](openapi/fawrypay-server-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fawrypay-server-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fawrypay-server-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://fawry.com/)
- [Portal](https://developer.fawrystaging.com/)
- [Getting Started](https://developer.fawrystaging.com/docs/get-started)
- [Documentation](https://developer.fawrystaging.com/docs-home)
- [Documentation](https://developer.fawrystaging.com/docs/server-apis/server-apis-overview)
- [Documentation](https://developer.fawrystaging.com/docs/sdks/sdks-overview)
- [Plugins](https://developer.fawrystaging.com/docs/plugins/plugins-overview)
- [Documentation](https://developer.fawrystaging.com/docs/express-checkout/checkout-integration-overview)
- [Documentation](https://developer.fawrystaging.com/docs/pay-by-link-overview)
- [Sign Up](https://fawrypay.online/merchant/register)
- [Support](https://developer.fawrystaging.com/contact-us)
- [Support](https://developer.fawrystaging.com/ticket-tracking)
- [GitHub Organization](https://github.com/FawryPay)
- [SDK](https://github.com/FawryPay/FawryPaySDK)
- [SDK](https://github.com/FawryPay/FawryPaySPM)
- [SDK](https://github.com/FawryPay/FawryPaySDK-AVL)
- [SDK](https://github.com/FawryPay/FawryPayAVLSPM)
- [SDK](https://github.com/FawryPay/FawryPaySDK-Registered)
- [SDK](https://github.com/FawryPay/FawryPaySDK-Microfinance)
- [Code Examples](https://github.com/FawryPay/Android-Fawrypay-Anonymous-sample)
- [Code Examples](https://github.com/FawryPay/Android-Fawrypay-AVL-sample)
- [Code Examples](https://github.com/FawryPay/iOS-Fawrypay-Anonymous-sample)
- [Code Examples](https://github.com/FawryPay/IOS-Fawrypay-AVL-Sample)
- [Code Examples](https://github.com/FawryPay/Flutter-Fawrypay-Anonymous-sample)
- [Code Examples](https://github.com/FawryPay/Flutter-Fawry-NFC-Sample)
- [Code Examples](https://github.com/FawryPay/ReactNative-Fawrypay-Anonymous-sample)
- [Code Examples](https://github.com/FawryPay/ReactNative-Fawrypay-Registered-Sample)
- [Product](https://www.fawry.com/business/acceptance/online-checkout/)
- [Product](https://www.fawry.com/business/acceptance/payment-link/)
- [Product](https://fawry.com/business/pay-out/)
- [Product](https://www.fawry.com/fawry-for-business/smes/commerce-enablement/)
- [Product](https://www.fawry.com/consumer/myfawry-app/)
- [Product](https://www.fawry.com/consumer/bill-payment/)
- [Investor Relations](https://fawry.com/investor-relations/)
- [Twitter](https://twitter.com/fawry)
- [LinkedIn](https://www.linkedin.com/company/fawry)
- [YouTube](https://www.youtube.com/@FawryEgypt)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
