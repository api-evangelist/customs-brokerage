# Customs Brokerage (customs-brokerage)

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
