# VideaHealth (videa-health)

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
