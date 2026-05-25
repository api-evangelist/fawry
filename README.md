# Fawry (fawry)

Fawry is Cairo-based Egypt's leading provider of e-payments and digital finance solutions. The FawryPay acceptance platform exposes a server-to-server REST API, native mobile SDKs (Android, iOS, Flutter, React Native), and certified e-commerce plugins (Magento, Shopify, WooCommerce) for charging cards (3DS), e-wallets, ValU, and bank installments, generating reference numbers payable across 250,000+ Fawry POS locations, refunding settled orders, and reconciling via signed server notifications. Fawry is publicly listed on the Egyptian Exchange as FWRY.CA.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/fawry/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Payments, E-Payments, Digital Finance, Fintech, Egypt, Cards, Wallets, Bill Payments, POS, Micro-Finance, Installments, 3D Secure, Refunds, Webhooks, Mobile SDK, E-Commerce Plugins, Magento, Shopify, WooCommerce

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### FawryPay Server API
Server-to-server REST API for creating FawryPay charges (card, 3DS, e-wallet, ValU, bank installments, PayAtFawry reference numbers), issuing refunds, cancelling unpaid orders, querying payment status, and listing bank installment plans. Authenticated per request via a merchant code and SHA-256 signature.

**Human URL:** [https://developer.fawrystaging.com/docs/server-apis/server-apis-overview](https://developer.fawrystaging.com/docs/server-apis/server-apis-overview)

- [Documentation — Server APIs Overview](https://developer.fawrystaging.com/docs/server-apis/server-apis-overview)
- [Documentation — Create Payment by Reference Number](https://developer.fawrystaging.com/docs/server-apis/create-payment-refno-apis)
- [Documentation — Refund](https://developer.fawrystaging.com/docs/server-apis/refund-issue-api)
- [Documentation — Cancel Unpaid Order](https://developer.fawrystaging.com/docs/server-apis/cancel-payment-api)
- [Documentation — Auth and Capture](https://developer.fawrystaging.com/docs/server-apis/auth-capture-payment-apis)
- [OpenAPI](openapi/fawrypay-server-api-openapi.yml)

## SDKs

- [FawryPaySDK (iOS, Objective-C)](https://github.com/FawryPay/FawryPaySDK)
- [FawryPaySDK Swift Package Manager](https://github.com/FawryPay/FawryPaySPM)
- [FawryPaySDK-AVL (iOS)](https://github.com/FawryPay/FawryPaySDK-AVL)
- [FawryPaySDK-Registered (iOS)](https://github.com/FawryPay/FawryPaySDK-Registered)
- [FawryPaySDK-Microfinance (iOS)](https://github.com/FawryPay/FawryPaySDK-Microfinance)

## Sample Apps

- [Android Anonymous](https://github.com/FawryPay/Android-Fawrypay-Anonymous-sample) / [Android AVL](https://github.com/FawryPay/Android-Fawrypay-AVL-sample)
- [iOS Anonymous](https://github.com/FawryPay/iOS-Fawrypay-Anonymous-sample) / [iOS AVL](https://github.com/FawryPay/IOS-Fawrypay-AVL-Sample)
- [Flutter Anonymous](https://github.com/FawryPay/Flutter-Fawrypay-Anonymous-sample) / [Flutter NFC](https://github.com/FawryPay/Flutter-Fawry-NFC-Sample)
- [React Native Anonymous](https://github.com/FawryPay/ReactNative-Fawrypay-Anonymous-sample) / [React Native Registered](https://github.com/FawryPay/ReactNative-Fawrypay-Registered-Sample)

## Features

- Server-to-server REST API for card, 3DS, e-wallet, ValU, installments, and PayAtFawry reference-number payments
- Refund and cancel-unpaid-order endpoints
- Pull (v2) and push (server notification v2) payment status reconciliation
- Express Checkout: self-hosted Checkout Button and Fawry-hosted Checkout Link
- Pay By Link for one-time and recurring invoices
- Native mobile SDKs across Android, iOS, Flutter, and React Native
- Certified e-commerce plugins for Magento 2, Shopify, and WooCommerce
- PayAtFawry retail acceptance across 250,000+ Fawry POS locations and partner channels in Egypt
- SHA-256 request signing with a per-merchant `secureKey`
- Multi-language (Arabic and English) payment flows
- Bank installment plan discovery API for partner banks

## Common

- [Website](https://fawry.com/)
- [Developer Portal](https://developer.fawrystaging.com/)
- [Getting Started](https://developer.fawrystaging.com/docs/get-started)
- [Mobile SDKs Overview](https://developer.fawrystaging.com/docs/sdks/sdks-overview)
- [E-Commerce Plugins Overview](https://developer.fawrystaging.com/docs/plugins/plugins-overview)
- [Express Checkout](https://developer.fawrystaging.com/docs/express-checkout/checkout-integration-overview)
- [Pay By Link](https://developer.fawrystaging.com/docs/pay-by-link-overview)
- [Merchant Registration](https://fawrypay.online/merchant/register)
- [Support / Contact](https://developer.fawrystaging.com/contact-us)
- [Ticket Tracking](https://developer.fawrystaging.com/ticket-tracking)
- [GitHub Organization](https://github.com/FawryPay)
- [Investor Relations](https://fawry.com/investor-relations/)
- [Twitter](https://twitter.com/fawry)
- [LinkedIn](https://www.linkedin.com/company/fawry)
- [YouTube](https://www.youtube.com/@FawryEgypt)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
