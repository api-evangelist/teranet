# Teranet (teranet)

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

Teranet Inc. is the private operator of Ontario's Electronic Land Registration System (ELRS) and the POLARIS land records database under a long-running concession with the Government of Ontario, and is the exclusive service provider for Manitoba's Land Titles System and Personal Property Registry. Founded in 1991, headquartered in Toronto and wholly owned by OMERS, Teranet sits at the base of the Canadian property value chain: it holds the authoritative title, parcel, writ and instrument record and resells it as commercial products — Teraview, OnLand, Teranet eXpress, GeoWarehouse, PurView, Teranet Xchange, DataConnect/ValueProtect AVM, TeraIntelligence — plus the Teranet-National Bank House Price Index. Its API posture is licensed access only. Teranet Connect is genuinely described by Teranet as an API (XML and web services over POLARIS and the Writs database), but it is licensed to legal-software vendors through an account manager, with no public documentation, no published base URL, no self-serve signup and no developer portal; Teranet's own support site states plainly that GeoWarehouse has no open API. No RESO certification was found — Teranet is a land registry, not an MLS — and the public record it stewards is sold back rather than published as open data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/teranet/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/teranet/refs/heads/main/apis.yml)

## Tags

- Real Estate
- Canada
- Land Registry
- Title
- Conveyancing
- Property Data
- Valuation
- AVM
- PropTech
- Government
- Geospatial

## Timestamps

- **Created:** 2026-07-26
- **Modified:** 2026-07-26

## APIs

### Teranet Connect

Teranet Connect is described by Teranet as an application programming interface providing secure access to Ontario's POLARIS land registration database and the Writs database, using XML and web services interfaces with rules-based routing. It lets legal document creation and management software vendors embed property search (by name, address or PIN), writ search by debtor name, instrument image retrieval and map data into their own applications. Access is licensed commercially through a Teranet account manager; no public technical documentation, base URL, sandbox or self-serve signup is published.

- **Human URL:** [https://www.teranet.ca/registry-solutions/province-of-ontario/teranet-connect/](https://www.teranet.ca/registry-solutions/province-of-ontario/teranet-connect/)
- **Base URL:** not published

#### Tags

- Land Registry
- Title
- Conveyancing
- Ontario
- Writs

#### Properties

- [Documentation](https://www.teranet.ca/registry-solutions/province-of-ontario/teranet-connect/)
- [Website](https://www.teranet.ca/registry-solutions/province-of-ontario/)

## Access Posture

- **Access gate:** partner-only — Teranet Connect is licensed to legal-software vendors through an account manager (info@teranet.ca), and every other data product is sold under a commercial data licence.
- **RESO posture:** no RESO certification found; Teranet is a land registry operator, not an MLS, and no RESO Web API, Data Dictionary, OData `$metadata` or UPI reference appears on any Teranet property.
- **Open data:** none. The Teranet-National Bank House Price Index publishes a free Composite 11 historical download, but under Terms of Use rather than an open licence.
- **Machine-readable contracts:** none published. See `review.yml` for every URL probed and its HTTP status.

## Common Properties

- [Website](https://www.teranet.ca/)
- [About](https://www.teranet.ca/about-teranet/)
- [Contact](https://www.teranet.ca/contact-us/)
- [Blog](https://www.teranet.ca/insights/)
- [Press Releases](https://www.teranet.ca/press-releases/)
- [Terms of Service](https://www.teranet.ca/terms-conditions/)
- [Privacy Policy](https://www.teranet.ca/privacy/)
- [Legal Notice](https://www.teranet.ca/legal-notice/)
- [LinkedIn](https://www.linkedin.com/company/teranet)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
