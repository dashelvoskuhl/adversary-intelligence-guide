# Adversary intelligence field guide

Links for people who study fraud operations or collect intelligence on the networks behind them. One line each.

Last checked: 2026-11-11.

## Decoys in production

- [Apate.ai](https://www.apate.ai/). AI agents pose as victims, keep fraudsters talking and send the intelligence to banks and telecoms. [TechCrunch, Oct 2026](https://techcrunch.com/2026/10/14/apate-sends-ai-agents-undercover-to-get-scammed-so-they-can-gather-fraud-intelligence/).
- [ScamBuster](https://github.com/laugiov/scambuster). Open source (MIT). Answers fraud emails and pulls indicators out of the replies. Shown at Black Hat USA 2026. [Dark Reading](https://www.darkreading.com/cyberattacks-data-breaches/turning-tables-email-scammers-scambuster).
- Daisy. O2's AI grandmother kept phone fraudsters on calls for up to 40 minutes. [TechCrunch](https://techcrunch.com/2024/11/15/ai-granny-scambaiter-wastes-telephone-fraudsters-time-with-boring-chat/), [NPR](https://www.npr.org/2024/12/10/nx-s1-5220362/daisy-ai-granny-o2-fraud-spam-prevention).

## Research on decoys

- [Anansi](https://arxiv.org/abs/2602.24223) (2026). Ten months of automated chats with the people behind fake job offers. 1,901 engaged.
- [Send to which account?](https://arxiv.org/abs/2509.08493) (2025). Five months, 2,600+ engagements. About 32% yielded mule account details.
- [The Imitation Game](https://arxiv.org/abs/2512.21371) (2025). LLM chatbots hold conversations inside cybercrime chat channels.
- [AI-in-the-Loop](https://arxiv.org/abs/2509.05362) (2025). Real time fraud detection and baiting that keeps user data private with federated learning.
- [CASE](https://arxiv.org/abs/2508.19932) (2025). A Google Pay India agent interviews likely victims. Enforcements rose 21%.
- [Automatic Scam-Baiting Using ChatGPT](https://arxiv.org/abs/2309.01586) (2023). A month of replies to 250+ real email fraudsters.
- [Scamming the Scammers](https://arxiv.org/abs/2303.13521) (2023). ChatGPT answers fraud mail to waste the sender's time.

## How the operations work

- [UNODC, Inflection Point](https://www.unodc.org/roseap/en/2025/04/cyberfraud-inflection-point-mekong/story.html) (2025). Cyberfraud operations are spreading beyond Southeast Asia.
- [FBI IC3 2025 report](https://www.ic3.gov/AnnualReport/Reports/2025_IC3Report.pdf) (PDF). 1,008,597 complaints and $20.877 billion in reported losses.
- [FTC Explore Data](https://www.ftc.gov/exploredata). Dashboards of US consumer fraud reports.
- [GASA Global State of Scams 2025](https://www.feedzai.com/global-state-of-scams-report-2025/). Survey of 46,000 adults in 42 countries. Its $442 billion loss figure is a survey estimate.

## Data

- [FTC Do Not Call reported calls](https://www.ftc.gov/policy-notices/open-government/data-sets/do-not-call-data). Phone numbers people reported for unwanted calls. New file each weekday. Unverified.
- [Chainabuse](https://chainabuse.com/). Public reports of crypto fraud, searchable by address. Run by TRM Labs. [API docs](https://docs.trmlabs.com/guides/chainabuse/welcome-to-chainabuse-api).
- [OpenPhish](https://openphish.com/). Phishing URL feed with a free tier.
- [PhishTank](https://phishtank.org/). Community verified phishing URLs. Free with registration.
- [phishunt](https://phishunt.io/feed/). Free feed of live phishing sites.
- [eth-phishing-detect](https://github.com/MetaMask/eth-phishing-detect). MetaMask's list of phishing domains that target Web3 users.

## Reporting

- US: [ReportFraud.ftc.gov](https://reportfraud.ftc.gov/) and the FBI's [IC3](https://www.ic3.gov/). Forward spam texts to 7726.
- UK: [Report Fraud](https://www.reportfraud.police.uk/), which replaced Action Fraud in December 2025. [NCSC phishing guidance](https://www.ncsc.gov.uk/collection/phishing-scams).
- Canada: [Canadian Anti-Fraud Centre](https://antifraudcentre-centreantifraude.ca/).
- Australia: [Scamwatch](https://www.scamwatch.gov.au/).
- Cross border: [econsumer.gov](https://www.econsumer.gov/).
- Phishing emails, any country: forward to reportphishing@apwg.org ([APWG](https://apwg.org/reportphishing/)).

## Sharing formats

- [STIX](https://oasis-open.github.io/cti-documentation/). The standard format for threat intelligence.
- [MISP](https://www.misp-project.org/). Open source platform for sharing indicators.
- [OpenCTI](https://github.com/OpenCTI-Platform/opencti). Open source intelligence platform built on STIX 2.
- [ScamClassifier](https://fedpaymentsimprovement.org/strategic-initiatives/payments-security/scams/scamclassifier-model/). The Federal Reserve's model for sorting cases by type.
- [MITRE Fight Fraud Framework](https://ctid.mitre.org/blog/2026/04/09/fraud-fighters-unite-with-mitre-f3/) (2026). A catalog of fraud tactics, sorted by behavior.

## Extraction libraries

- [reStalker](https://pypi.org/project/restalker/). Python, MIT. Pulls indicators and entities out of text or binary sources, darknet addresses included.
- [ioc-finder](https://pypi.org/project/ioc-finder/). Python. Finds and parses indicators of compromise in text.
- [iocextract](https://pypi.org/project/iocextract/). Python. Extracts indicators, defanged ones included.
- [ioc-extractor](https://github.com/ninoseki/ioc-extractor). TypeScript, MIT. Extracts indicators from a block of text.

---

Maintained by [Dash Voskuhl](https://dashvoskuhl.com).
