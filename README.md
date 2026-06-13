# IRS

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
