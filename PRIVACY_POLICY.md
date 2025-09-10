# FODMAP Living Privacy Policy

Effective Date: 2025-09-06  
Version: 1.0

_Last Updated: 2025-09-06_

Thank you for using FODMAP Living. This Privacy Policy explains how we collect, use, store, and share information when you use the App and related services (collectively, the "Services").

If you do not agree with this Policy, please do not use the Services. By using the Services you consent to the practices described here.

## At a Glance
- We process your meal images and text to provide results, then discard server-side copies after transient processing.
- Your meal history (including derived analysis and any local image copies/thumbnails) is stored on your device and can be cleared in the app.
- We do not sell your data and we do not use targeted advertising.
- Core service providers we rely on: Apple (in-app purchases), RevenueCat (subscription entitlements), OpenAI (AI inference), and Cloudflare (hosting/routing). We update the Policy for material changes.

## 1. Overview
FODMAP Living helps users analyze meal photos and ingredient inputs to assist in identifying potential FODMAP-related triggers. We focus on minimizing personal data collection and retaining only what is needed for core functionality, subscription management, security, and improvement.

FODMAP Living is not a medical device and does not provide medical advice. Always consult a qualified healthcare professional before making dietary changes.

## 2. Data We Collect
We collect only the categories of data necessary to operate and improve the Services:

### 2.1 Account & Authentication Data
- Pseudonymous user identifier (generated token / app user ID)
- Authentication token (JWT) stored securely on device
- Subscription entitlement state (active/inactive, product identifiers)

### 2.2 Usage & Request Data
- Meal analysis requests (structured ingredient text, model output JSON)
- Problem analysis queries and responses
- Timestamps of requests for usage limit enforcement
- Token usage counters (daily / monthly aggregate)

### 2.3 Images
- Meal photos you voluntarily submit for analysis. Images are transmitted securely to the backend and then to AI processing providers (e.g., OpenAI) transiently. We do not store images on our servers beyond transient processing. For your convenience, images (or thumbnails) may be stored locally on your device to power meal history; you can clear history in-app to delete these local copies.

### 2.4 Device & Technical Data
- Approximate device model (as exposed by iOS APIs)
- App version & build number
- Network request metadata (success/failure, latency, HTTP status)
- Crash / error diagnostics (if crash reporting added in future — will update Policy)

### 2.5 Purchase & Subscription Data
- Product identifiers (e.g., monthly / yearly plan IDs)
- Transaction status (active, expired, in grace period) via RevenueCat
- Renewal status & trial/intro eligibility where applicable

### 2.6 Optional User Inputs
- Manually edited ingredient notes or overrides (if feature enabled later)
- Feedback / support messages (if added later)

We do not intentionally collect: precise location, health records, contacts, calendars, or raw device identifiers like advertising ID (IDFA) unless required by an added feature (we would update this Policy first).

## 3. How We Use Data
We use collected data to:
- Provide core analysis features and generate ingredient / FODMAP insights
- Enforce usage limits and fair use protections
- Manage subscriptions and entitlement access
- Improve accuracy, reliability, and user experience (aggregate & anonymized trends)
- Detect abuse, fraud, and security anomalies
- Comply with legal obligations
- Communicate important service or policy updates

## 4. Legal Bases for Processing (EEA / UK Users)
If you are in the European Economic Area or the UK, we rely on these legal bases:
- Performance of a contract: delivering the Services & subscription features
- Legitimate interests: preventing abuse, improving the App, ensuring reliability
- Consent: where required for optional features (we will prompt clearly)
- Legal obligation: record-keeping, compliance with lawful requests

## 5. Sharing & Service Providers
We limit sharing to essential processors and infrastructure providers:

| Provider | Purpose | Data Categories | Region / Notes |
|----------|---------|-----------------|----------------|
| Apple (In-App Purchases) | Payment & subscription transactions | Purchase metadata | As per App Store territory |
| RevenueCat | Subscription management & entitlements | Product IDs, status, pseudonymous appUserID | Global (see RevenueCat DPA) |
| OpenAI (or compatible AI API) | Image / text model inference | Transient meal text, derived image embeddings or descriptions | Processing only; no long-term training retention (per provider terms) |
| Cloudflare Workers / Durable Objects | Hosting, rate limiting, caching | Request metadata, usage counters, transient images | Regional edge w/ global distribution |
| Error / Crash Reporting (future optional) | Diagnostics | Crash logs, non-sensitive diagnostics | Added only if implemented (Policy update) |

We do not sell your personal data.
We may disclose information if required by law, to protect rights/safety, or in a merger/acquisition (with continuity of protections or notice).

## 6. Data Retention
- Usage counters: reset and rolled over daily / monthly; historical aggregates may be anonymized.
- Subscription state: retained while account/subscription is active and for a reasonable audit period after lapse (e.g., 12 months) for fraud prevention.
- Meal analysis outputs: stored locally on your device to provide history features; you may clear history in the app to delete these local records. We do not store these outputs on our servers beyond transient processing.
- Images (local copies): stored locally on your device to power meal history; you may clear history in the app or delete the app to remove these local copies. We do not store images on our servers beyond transient processing.
- Transient images: discarded promptly after model processing unless flagged for short-term debugging (then removed within 7 days).
- Authentication tokens: rotated per security policy or upon logout.

## 7. Security
We employ industry-standard measures:
- Transport encryption (HTTPS)
- Scoped authentication tokens (JWT) stored via Keychain (migration in progress)
- Rate limiting & anomaly detection
- Principle of least privilege for backend components
- Secrets rotation practices documented internally

No system is perfectly secure; we encourage reporting vulnerabilities via the contact methods below.

## 8. Your Rights (Where Applicable)
Depending on jurisdiction you may have rights to access, rectify, delete, restrict, object, or port data. Submit a request via the contact email below. We will verify limited necessary details (pseudonymous ID). If we cannot fully delete due to legal or fraud prevention obligations, we will explain.

We currently do not conduct profiling producing legal effects. We do not sell data nor use it for targeted advertising.

## 9. Children's Privacy
The Services are not directed to children under 13 (or minimum age in your jurisdiction). We do not knowingly collect personal data from children. If you believe a child provided data, contact us for removal.

## 10. International Transfers
Data may be processed in regions where our providers operate (e.g., United States, EU). We rely on standard contractual clauses or equivalent safeguards where required.

## 11. Changes to This Policy
We may update this Policy to reflect changes in practices or legal requirements. Material changes will be signaled in-app or via update notes. Continued use after the effective date constitutes acceptance.

## 12. Contact
Questions or requests:  
Email: fodmapai@gmail.com 
Subject line: "Privacy Request – FODMAP Living"

## 13. Medical & Nutritional Disclaimer
FODMAP Living provides AI-assisted ingredient interpretation and potential FODMAP considerations. It does NOT provide medical, diagnostic, or personalized dietary advice. Always consult a qualified healthcare professional or registered dietitian before making dietary changes, especially if you have IBS, allergies, or other medical conditions. Do not ignore professional advice because of information provided by the App.

---
If any translation differs from the English version, the English version controls.
