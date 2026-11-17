# Sources

[README](README.md) · [Provenance](provenance.md) · **Sources** · [Timeline](timeline.md) · [Assessment](assessment.md) · [Comparison](comparison.md) · [Open questions](open-questions.md) · [Source check](source-check.md)

What each source says about NSANet, and how far each can be trusted, as of 17 November 2026. For the claim-by-claim table, see [provenance.md](provenance.md). A later pass that opened the sources is in [source-check.md](source-check.md).

> **Nearly all technical detail since 2007 rests on one pseudonymous hobbyist blog**, [Electrospaces.net](#electrospacesnet). The only primary material seen directly is 19 to 23 years old, and the current reporting is anonymous-source journalism with no technical content.

| Tier | Source | Date of underlying evidence | Caveat |
| --- | --- | --- | --- |
| Primary | [Leaked NSA documents](#primary-documents) | 2003 to 2007, one item circa 2012 | Authentic but old |
| Tertiary | [Wikipedia](#wikipedia) | 1998 and 2004 for the two reports it cites; none recorded for its general description | The reports it cites were not checked |
| Secondary | [Electrospaces.net](#electrospacesnet) | 2006 to 2015, one claim undated | One pseudonymous hobbyist blog, read in part |
| Current: anonymous-source journalism | [November 2026 reporting](#november-2026-reporting) | Nov 2026, with the exceptions noted in the section | Anonymous sources, no technical detail |

## Primary documents

**Tier:** primary. **Date of underlying evidence:** 2003 to 2007 for SIDtoday, circa 2012 for the TAO presentation.

Snowden-era NSA documents: the SIDtoday newsletter as published by The Intercept, and one TAO presentation.

- The Intercept's SIDtoday archive (internal newsletter of the Signals Intelligence Directorate) contains a 13 November 2006 article, "Intelink: Make the Connection," which states that "NSANet may be the 'home' system for NSAers" and contrasts it with Intelink, the IC-wide portal. It notes almost 14,000 Intelink accounts in the NSA Washington group at that time.
- Every SIDtoday article carries the boilerplate: "SIDtoday articles may not be republished or reposted outside NSANet without the consent of S0121."
- The page banner on these documents reads "HIGHEST POSSIBLE CLASSIFICATION IS TOP SECRET // SI / TK // REL TO USA AUS CAN GBR NZL," consistent with NSANet operating at the TS/SCI level and being shared across the Five Eyes.
- Other SIDtoday items confirm NSANet as the platform from which staff reach Intelink tools (e.g. the ICDS search tool note: "You must be a US citizen and have an Intelink account to access ICDS from NSANet").
- A TAO (Tailored Access Operations) presentation in the Snowden archive shows a data flow from victim machines through a network called WAITAUTO to TAONet, then through a TAONet/NSANet DMZ to repositories and analytic tools on NSANet.

**Provenance:** these are leaked internal documents published by The Intercept with editorial review. They are authentic but 19–23 years old. The TAO presentation is the exception: it dates from circa 2012, and it was seen only as reproduced by [Electrospaces](#electrospacesnet), not opened directly.

## Wikipedia

**Tier:** tertiary. **Date of underlying evidence:** 1998 and 2004 for the two reports it cites. None is recorded for the general description in the first bullet: a task in [open-questions.md](open-questions.md#needs-sourcing).

- Describes NSANet as the official NSA intranet, classified up to TS/SCI, supporting intelligence sharing between NSA and the SIGINT agencies of the other Five Eyes nations; management delegated to Central Security Service Texas; fibre-optic and satellite links almost entirely separated from the public Internet.
- Cites a 1998 report that NSANet, along with NIPRNet and SIPRNet, had "significant problems with poor search capabilities, unorganized data and old information," and a 2004 report that it ran over twenty commercial off-the-shelf operating systems.

**Provenance:** tertiary; the 1998 and 2004 citations are the earliest public references found, and predate Snowden. Neither report was checked directly.

## Electrospaces.net

**Tier:** secondary. **Date of underlying evidence:** 2006 to 2015; the phone claim is undated. The page is dated 2015 and was updated in 2025.

A pseudonymous Dutch blog (author "P/K") specialising in SIGINT and COMSEC, widely cited by journalists in this niche. Its entry on NSANet gives:

- Classification: TOP SECRET/SCI, colour code yellow (same as JWICS; SIPRNet is red, NIPRNet green).
- Secured by TACLANE (KG-175) in-line network encryptors (sourced to a cleared-jobs posting).
- Address format originally subdomain.domain.nsa, replaced in 2007 by nsa.ic.gov (sourced to FOIA'd NSA executive messages).
- Access: Five Eyes SIGINT users, polygraph required; roughly 30,000 users.
- Controlled by NSA, management delegated to CSS Texas.
- Hosted applications listed include InfoWorkSpace, WikiInfo, SIDToday, TREASUREMAP, MARINA, TURBINE, PRESSUREWAVE, INTERQUAKE, CATAPULT and others.
- Phone service: NSTS phones connect via fibre to the NSANet service delivery point router.
- A 2006 NSOC photo caption describes a KVM switch with two green (Unclassified), one red (Secret) and one orange-and-yellow (TS/SCI) labelled network. Orange appears only in this caption; the standard code given for TS/SCI networks is yellow.

**Provenance:** a hobbyist compilation, but each line is footnoted to a Snowden document, FOIA release, job advert, official photo or, for the phone claim, a Quizlet flashcard set. Treat it as a well-indexed secondary source, not an authority. Only the first portion of the page text was read, and every claim above was quoted rather than paraphrased.

Two lines carry a caveat of their own in the provenance table. The phone claim cites a Quizlet flashcard set, which the table calls a weak source, and is undated. The FOIA document behind the 2007 domain change was not opened here. Sourcing and dates, row by row, are in the [provenance table](provenance.md#claim-by-claim). The statement that the blog is widely cited by journalists in this niche names no source yet: a task in [open-questions.md](open-questions.md#needs-sourcing).

**Why it matters:** nearly all technical detail since 2007 rests on this one blog, including the TAO presentation under [Primary documents](#primary-documents), which was seen only as Electrospaces reproduces it.

## November 2026 reporting

**Tier:** current reporting, anonymous-source journalism. **Date of underlying evidence:** Nov 2026. Two items are exceptions. For the 2000 crash, CNN quotes an agency spokesperson from 2000, which the provenance table records as journalism citing an on-record official statement, dated Jan 2000. For the 2013 public website incident that The Record cites, no source type is recorded.

- CNN (17 Nov 2026) reported, citing six sources, that the network "called NSA Net" which "allows employees to communicate classified information internally" had gone down, with no evidence of a cyberattack at that point and staggered measures enacted while scope was assessed. Forbes, The Record, ABC and others repeated the same framing.
- These reports confirm the network's continued existence and its role as the internal classified communications platform, but give no technical detail.

Who is behind each report:

| Outlet | Sourcing |
| --- | --- |
| CNN, 17 Nov 2026 | Six anonymous sources. For the 2000 crash, an agency spokesperson quoted at the time |
| Forbes, The Record, ABC, WRAL, Ynet | Repeat CNN's framing. The Record adds the 2013 public website incident |
| Wall Street Journal, via Jerusalem Post | One person familiar |
| Nextgov/FCW | Six people familiar; four of them said it may be linked to a series of software upgrades |
| New York Times, syndicated | One person |

What each report said is in the [timeline](timeline.md#17-november-2026); the 2000 crash is under [January 2000](timeline.md#january-2000) and the 2013 public website incident under [2013](timeline.md#2013).

**Provenance:** anonymous-source journalism with no technical content. The denials are low-information: "no evidence of a cyberattack" on day one describes what has been found, not what has been ruled out. How that is weighed is in the [assessment](assessment.md#cyberattack-versus-self-inflicted).

## Sources consulted

- [Wikipedia, "National Security Agency" (NSANet section)](https://en.wikipedia.org/wiki/National_Security_Agency#NSANet)
- [Electrospaces.net, "US military and intelligence computer networks"](https://www.electrospaces.net/2015/03/us-military-and-intelligence-computer.html) (11 March 2015, updated 12 September 2025)
- The Intercept, [Snowden Archive / SIDtoday files](https://theintercept.com/snowden-sidtoday/): ["Intelink: Make the Connection"](https://theintercept.com/snowden-sidtoday/5987444-intelink-make-the-connection/) (13 Nov 2006), ["Welcome to SIDtoday,"](https://theintercept.com/snowden-sidtoday/2829957-welcome-to-sidtoday/) ["Announcing ICDS,"](https://theintercept.com/snowden-sidtoday/3991319-announcing-icds-a-new-intelink-intelligence/) and others
- CNN, ["Highly classified US national security communications network goes down"](https://www.cnn.com/2026/11/17/politics/highly-classified-national-security-communications-network-goes-down) † (17 Nov 2026)
- [Forbes](https://www.forbes.com/sites/zacharyfolk/2026/11/17/national-security-agencys-highly-classified-internal-network-has-gone-down-report-says/) †, [The Record](https://therecord.media/nsa-net-disruptions), [ABC News 4](https://abcnews4.com/news/nation-world/nsas-national-security-agency-classified-internal-network-is-down-sources-say-no-evidence-cyberattack-communications), [Ynetnews](https://www.ynetnews.com/article/rkhmwxccgg) coverage of the same outage (17 Nov 2026)

Also cited:

- Wall Street Journal, ["Classified U.S. Intelligence System Is Down for Now, U.S. Officials Say"](https://www.wsj.com/politics/national-security/classified-u-s-intelligence-system-is-down-for-now-u-s-officials-say-aa09b6d1) † (17 Nov 2026), via The Jerusalem Post, ["NSA's highly classified internal communications network shuts down, linked to software update - WSJ"](https://www.jpost.com/international/article-915216) (17 Nov 2026)
- Nextgov/FCW, ["Classified NSA communications network down, people familiar say"](https://www.nextgov.com/digital-government/2026/11/classified-nsa-communications-network-down-people-familiar-say/417277/) (17 Nov 2026)
- New York Times, ["Classified N.S.A. Network Goes Down, Causing Work Disruptions"](https://www.nytimes.com/2026/11/17/us/politics/nsa-down-network-outage-nsanet.html) † (17 Nov 2026), syndicated
- WRAL, ["Highly classified U.S. national security communications network goes down, sources say"](https://www.wral.com/news/local/national-security-communications-network-outage-november-2026/) (17 Nov 2026), carrying the CNN wire story
- The comparison sources, listed in [comparison.md](comparison.md#sources)

Links were added on 17 November 2026, in a later pass that opened each page and compared it with the notes: see [source-check.md](source-check.md). † marks a page that refuses automated fetching: its link and title come from search listings or from other pages that cite it, and it was not opened in that pass. Opening those pages is a task in [open-questions.md](open-questions.md#needs-sourcing).

[Back to README](README.md)
