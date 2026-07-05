# VideaHealth (videa-health)

VideaHealth (marketed as **VideaAI**, at [videa.ai](https://www.videa.ai)) is an FDA-cleared dental artificial-intelligence platform. It analyzes dental radiographs to detect clinical findings - such as caries, bone loss, calculus, and periapical lesions - and to surface aligner and implant treatment opportunities. VideaAI is designed as **ambient, chairside AI**: as soon as an X-ray is captured, the platform analyzes the image in the background and returns findings directly inside the tools clinicians already use. VideaAI reports analyzing hundreds of millions of X-rays annually across tens of thousands of clinicians and many of the largest dental service organizations (DSOs) in North America.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/videa-health/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/videa-health/refs/heads/main/apis.yml)

## API Access Model — Partner-Gated / Embedded (Honest Stub)

**VideaHealth does not publish a public, self-serve developer API.** As of this writing there is:

- **No public REST API reference or base URL**
- **No developer portal, developer sign-up, or self-serve onboarding**
- **No SDK or published OpenAPI definition**
- **No documented WebSocket (`ws://` / `wss://`) or SSE streaming interface**

Instead, VideaAI is delivered **business-to-business and partner-gated**. The AI is embedded directly into the customer's existing practice-management and imaging software through commercial integration agreements. Organizations engage VideaHealth via a sales/demo process ("Book a Demo"); pricing is **contact-sales only** and is not published.

This repository is therefore recorded as an **honest gated stub**: `apis: []` in `apis.yml`. No endpoints are asserted as real. The logical capability areas below are an explicit *model* of what a VideaHealth partner/developer API would plausibly expose based on the product's described behavior — they are **not documented, not confirmed, and must not be treated as real endpoints**.

## Modeled Logical APIs (not documented — illustrative only)

- **Image / Radiograph Analysis** — submit a dental radiograph (bitewing, periapical, panoramic) for AI analysis.
- **Findings / Detections** — retrieve detected clinical findings (caries, bone loss, calculus, periapical lesions) with per-tooth localization and confidence scores.
- **Studies** — group radiographs and findings into a patient study/exam and retrieve results.
- **Integrations** — bind VideaAI into a practice-management or imaging system so captured X-rays are automatically analyzed and findings are surfaced in-context.

## Embedded Integrations (product-level, not developer APIs)

VideaAI advertises embedding across the dental software ecosystem, including practice-management systems such as **Dentrix Core, Dentrix Ascend, Dentrix Enterprise, Denticon, Open Dental, and Eaglesoft**, and imaging software such as **Carestream, Dexis, Apteryx XVWeb, SOTA, Dentsply Sirona Sidexis, MiPACS, Gendex VixWin, Patterson Imaging, and others**. These are commercial, embedded integrations delivered by VideaHealth — not publicly documented APIs a third-party developer can call.

## Tags

- Dental
- Healthcare
- Artificial Intelligence
- Medical Imaging
- Radiograph Analysis
- Diagnostics
- Computer Vision
- FDA Cleared
- Gated API

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## Common Properties

- [Website](https://www.videa.ai)
- [LinkedIn](https://www.linkedin.com/company/videaai)
- [Resources](https://videa.ai/resources)
- [Platform](https://www.videa.ai/platform)
- [News](https://www.videa.ai/news)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
