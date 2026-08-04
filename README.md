# Customs Brokerage (customs-brokerage)

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

Customs brokerage is the licensed practice of clearing imported and exported goods through customs authorities on behalf of importers and exporters. Brokers prepare and file entry documentation, classify merchandise, calculate duties and fees, manage Partner Government Agency requirements, and represent clients in customs matters. In the United States, brokers are licensed by CBP and primarily file through the Automated Commercial Environment (ACE) via EDI. APIs in this space are typically embedded in customs broker software and global trade management platforms rather than offered as standalone advisory APIs.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/customs-brokerage/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** Public
- **x-type:** topic

## Tags

- ABI, ACE, AES, Brokerage, Cargo Release, Compliance, Customs, Customs Brokers, Duties, EDI, Entry Summary, Exports, Freight Forwarding, Imports, PGA, Trade

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

No standalone customs brokerage APIs are catalogued here. Brokers integrate with national customs authorities through EDI standards (ABI / CATAIR for ACE, AESTIR for AES), and customer-facing APIs are typically delivered by customs broker software vendors and freight forwarder TMS platforms.

## Authoritative References

- [CBP Automated Commercial Environment](https://www.cbp.gov/trade/automated)
- [CBP Customs Brokers Program](https://www.cbp.gov/trade/programs-administration/customs-brokers)
- [ACE CATAIR (Customs and Trade Automated Interface Requirements)](https://www.cbp.gov/trade/ace/catair)
- [WCO SAFE Framework](https://www.wcoomd.org/en/topics/facilitation/instrument-and-tools/frameworks-of-standards/safe_package.aspx)
- [Authorized Economic Operator (AEO)](https://www.wcoomd.org/en/topics/facilitation/instrument-and-tools/tools/authorized-economic-operator-package.aspx)
- [U.S. Harmonized Tariff Schedule](https://hts.usitc.gov/)

## Industry Associations

- [National Customs Brokers and Forwarders Association of America (NCBFAA)](https://www.ncbfaa.org/)
- [Canadian Society of Customs Brokers (CSCB)](https://www.cscb.ca/)

## Vocabulary

- **ABI** — Automated Broker Interface; the EDI channel into ACE used by licensed brokers and self-filers.
- **CATAIR** — Customs and Trade Automated Interface Requirements; the published ACE EDI specifications.
- **Entry Summary** — CBP Form 7501; details merchandise, value, classification, and duties.
- **Cargo Release** — CBP authorization for goods to enter U.S. commerce.
- **Power of Attorney (POA)** — Authorization for a broker to act on behalf of an importer.
- **Bond** — Continuous or single-transaction surety required for entries.
- **PGA (Partner Government Agency)** — Other federal agencies (FDA, USDA, EPA, etc.) with admissibility requirements integrated through ACE.
- **AEO** — Authorized Economic Operator; trusted-trader program under the WCO SAFE Framework.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
