# Sources

[README](README.md) · [Provenance](provenance.md) · **Sources** · [Timeline](timeline.md) · [Assessment](assessment.md) · [Comparison](comparison.md) · [Open questions](open-questions.md)

What each source says about NSANet, and how far each can be trusted. For the same material claim by claim, see [provenance.md](provenance.md).

> **Nearly all technical detail since 2007 rests on one pseudonymous hobbyist blog.** The only primary material is 19 to 23 years old. Everything technical since then comes through [Electrospaces.net](#electrospacesnet), and the current reporting is anonymous-source journalism with no technical content.

| Tier | Source | Date of underlying evidence | Caveat |
| --- | --- | --- | --- |
| Primary | [Leaked NSA documents](#primary-documents) | 2003 to 2007, one item circa 2012 | Authentic but old |
| Tertiary | [Wikipedia](#wikipedia) | 1998 and 2004 | The reports it cites were not checked |
| Secondary | [Electrospaces.net](#electrospacesnet) | 2006 to 2015 | One pseudonymous hobbyist blog, read in part |
| Current | [November 2026 reporting](#november-2026-reporting) | Nov 2026 | Anonymous sources, no technical detail |

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

**Tier:** tertiary. **Date of underlying evidence:** 1998 and 2004, the two reports it cites.

- Describes NSANet as the official NSA intranet, classified up to TS/SCI, supporting intelligence sharing between NSA and the SIGINT agencies of the other Five Eyes nations; management delegated to Central Security Service Texas; fibre-optic and satellite links almost entirely separated from the public Internet.
- Cites a 1998 report that NSANet, along with NIPRNet and SIPRNet, had "significant problems with poor search capabilities, unorganized data and old information," and a 2004 report that it ran over twenty commercial off-the-shelf operating systems.

**Provenance:** tertiary; the 1998 and 2004 citations are the earliest public references found, and predate Snowden. Neither report was checked directly.

## Electrospaces.net

**Tier:** secondary. **Date of underlying evidence:** 2006 to 2015. The page is dated 2015 and was updated in 2025.

A pseudonymous Dutch blog (author "P/K") specialising in SIGINT and COMSEC, widely cited by journalists in this niche. Its entry on NSANet gives:

- Classification: TOP SECRET/SCI, colour code yellow (same as JWICS; SIPRNet is red, NIPRNet green).
- Secured by TACLANE (KG-175) in-line network encryptors (sourced to a cleared-jobs posting).
- Address format originally subdomain.domain.nsa, replaced in 2007 by nsa.ic.gov (sourced to FOIA'd NSA executive messages).
- Access: Five Eyes SIGINT users, polygraph required; roughly 30,000 users.
- Controlled by NSA, management delegated to CSS Texas.
- Hosted applications listed include InfoWorkSpace, WikiInfo, SIDToday, TREASUREMAP, MARINA, TURBINE, PRESSUREWAVE, INTERQUAKE, CATAPULT and others.
- Phone service: NSTS phones connect via fibre to the NSANet service delivery point router.
- A 2006 NSOC photo caption describes a KVM switch with two green (Unclassified), one red (Secret) and one orange-and-yellow (TS/SCI) labelled network. Orange appears only in this caption; the standard code given for TS/SCI networks is yellow.

**Provenance:** a hobbyist compilation, but each line is footnoted to a Snowden document, FOIA release, job advert or official photo. Treat it as a well-indexed secondary source, not an authority. Only the first portion of the page text was read, and every claim above was quoted rather than paraphrased.

Two lines are weaker than the rest. The phone claim rests on a Quizlet flashcard set and is undated, and the FOIA document behind the 2007 domain change was not opened here. Line-by-line sourcing and dates are in the [provenance table](provenance.md#claim-by-claim).

**Why it matters:** nearly all technical detail since 2007 rests on this one blog, including the TAO presentation under [Primary documents](#primary-documents), which was seen only as Electrospaces reproduces it.

## November 2026 reporting

**Tier:** anonymous-source journalism. **Date of underlying evidence:** Nov 2026.

- CNN (17 Nov 2026) reported, citing six sources, that the network "called NSA Net" which "allows employees to communicate classified information internally" had gone down, with no evidence of a cyberattack at that point and staggered measures enacted while scope was assessed. Forbes, The Record, ABC and others repeated the same framing.
- These reports confirm the network's continued existence and its role as the internal classified communications platform, but give no technical detail.

Who is behind each report:

| Outlet | Sourcing |
| --- | --- |
| CNN, 17 Nov 2026 | Six anonymous sources. For the 2000 crash, an agency spokesperson quoted at the time |
| Forbes, The Record, ABC, WRAL, Ynet | Repeat CNN's framing. The Record adds the 2013 public website incident |
| Wall Street Journal, via Jerusalem Post | One person familiar |
| Nextgov/FCW | Six people familiar; four of them point to software upgrades |
| New York Times, syndicated | One person |

What each report said is in the [timeline](timeline.md#17-november-2026).

**Provenance:** anonymous-source journalism with no technical content. The denials are low-information: "no evidence of a cyberattack" on day one describes what has been found, not what has been ruled out. How that is weighed is in the [assessment](assessment.md#cyberattack-versus-self-inflicted).

## Sources consulted

- Wikipedia, "National Security Agency" (NSANet section)
- Electrospaces.net, "US military and intelligence computer networks" (11 March 2015, updated 12 September 2025)
- The Intercept, Snowden Archive / SIDtoday files: "Intelink: Make the Connection" (13 Nov 2006), "Welcome to SIDtoday," "Announcing ICDS," and others
- CNN, "Highly classified US national security communications network goes down" (17 Nov 2026)
- Forbes, The Record, ABC News 4, Ynetnews coverage of the same outage (17 Nov 2026)

Also cited, so far by outlet only:

- Wall Street Journal, via Jerusalem Post (Nov 2026)
- Nextgov/FCW (Nov 2026)
- New York Times, syndicated (Nov 2026)
- WRAL (Nov 2026)
- The comparison sources, listed in [comparison.md](comparison.md#sources)

URLs, and titles for the second group, are not recorded yet. Both are tasks in [open-questions.md](open-questions.md#needs-sourcing).

[Back to README](README.md)
