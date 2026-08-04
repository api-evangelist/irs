# IRS

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

The US Internal Revenue Service (IRS) provides REST and Application-to-Application (A2A) APIs for tax information access, income verification, information return filing, and taxpayer account data. Authorized applications can integrate with IRS e-Services for TIN matching, the Income Verification Express Service (IVES), the Information Return Intake System (IRIS) for 1099 series filings, the Modernized e-File (MeF) system, and the Transcript Delivery System (TDS).

## APIs

- **TIN Matching API** - Match taxpayer name/TIN combinations against IRS records before filing information returns. Interactive (25 per session) and bulk (up to 100,000 per submission) modes available.
- **Income Verification Express Service (IVES) API** - A2A API for authorized lenders and financial institutions to request tax transcripts for income verification. $4 per transcript.
- **Information Return Intake System (IRIS) API** - A2A API for electronic filing of 1099 series information returns. Free for enrolled participants.
- **Modernized e-File (MeF) API** - A2A API for electronic submission of business and individual tax returns. Free for authorized software developers.
- **Transcript Delivery System (TDS) API** - API for authorized tax professionals to retrieve tax transcripts. Free for enrolled e-Services participants.

## Getting Started

All IRS APIs require enrollment in IRS e-Services and obtaining an API client ID.

- Developer Portal: https://www.irs.gov/tax-professionals/get-an-api-client-id
- e-Services Enrollment: https://la.www4.irs.gov/esrv/esam/pages/landingPage.xhtml
- e-Help Desk: 866-255-0654

## Authentication

IRS APIs use OAuth-style authentication with a Client ID and signed JWT Bearer tokens. All connections require TLS 1.2 or higher with SHA-256 or higher cryptographic signatures.

## Resources

- [Website](https://www.irs.gov/)
- [Developer Portal](https://www.irs.gov/tax-professionals/get-an-api-client-id)
- [MeF Status Page](https://www.irs.gov/e-file-providers/modernized-e-file-mef-status)
- [Newsroom](https://www.irs.gov/newsroom)
- [LinkedIn](https://www.linkedin.com/company/irs)
- [X](https://x.com/irsnews)
