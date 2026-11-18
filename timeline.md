# Timeline

[README](README.md) · [Provenance](provenance.md) · [Sources](sources.md) · **Timeline** · [Assessment](assessment.md) · [Comparison](comparison.md) · [Open questions](open-questions.md) · [Source check](source-check.md)

The November 2026 outage and the earlier outages on the public record, newest first. Each entry says who reported it and what kind of source that is, or says that this is not recorded.

Only one comparable precedent is on the public record: the [January 2000](#january-2000) crash. No prior public reporting on NSANet instability was found before the week of 17 November 2026.

<!--
New entries go directly below this comment, newest first. If the date already has an entry, add to that entry instead of starting a second heading with the same date: other files link to the heading. Template:

## DD Month YYYY

**Headline in one line.**

- Outlet: what it reported, and how it was sourced (for example "two people familiar").

Source type: for example anonymous-source journalism, or an on-record statement.

Add any new outlet to the Sources list at the end of this file and to sources.md.

Then update the status table at the top of README.md.
-->

## 17 November 2026

**NSANet reported down; later the same day the NSA called it scheduled maintenance.**

Later on 17 November, after the first reports, the picture changed. This block comes from the pass that opened the sources; see [source-check.md](source-check.md).

- NSA statement, carried by The Record, ABC News 4 and Ynetnews (the last crediting Reuters): the network had a temporary degradation during scheduled routine maintenance, some internal systems were affected, and mission-critical capabilities stayed operational, on infrastructure built with layers of redundancy. The NSA's own press release was not opened.
- The Record, from its own sources and crediting CNN with reporting first, said the network was not completely shut down but giving intermittent service, and that it had been unstable for weeks.
- ABC News 4 was rewritten under the headline "NSA says classified network experienced temporary disruption during routine maintenance"; it no longer says the network is down and no longer cites six people.
- The later CNN wire version (read in CBS 58's copy) and Ynetnews said intelligence sharing with the Five Eyes partners was not affected; the later CNN version added a White House spokesperson saying there was no evidence of a cyberattack.

Source type: an on-record agency statement, relayed by the outlets above. It is the first official account and firmer than the anonymous-source reporting below. The reading rule applies to it too.

The CNN report, read in WRAL's copy of the early wire version:

- CNN reported, citing six sources, that the network "called NSA Net" which "allows employees to communicate classified information internally" had gone down, with no evidence of a cyberattack at that point and staggered arrivals for personnel while scope was assessed. The later version writes NSANet as one word.
- Forbes, ABC News 4 and Ynetnews repeated the same framing before the last two were rewritten. Forbes was not opened.

Later reporting:

- Wall Street Journal (via Jerusalem Post): a person familiar said the NSA was "simply updating its software to patch the system," that NSANet would only be temporarily offline, and there was no evidence of a cyberattack. All four points rest on one sentence of the Jerusalem Post page.
- Nextgov/FCW: six people familiar said the outage slowed analysts' workflows and had staff rearranging their arrivals; four of them said it may be linked to a series of software upgrades on the network. Nextgov describes NSA Net as "the primary platform for transmitting top-secret data."
- New York Times (syndicated; the source check read a repost on DNYUZ): one person said NSANet had been unstable for weeks, fuelling frustration in the workforce. The Record carries the same claim of weeks of instability.

Source type: anonymous-source journalism throughout this part. These reports confirm the network's continued existence and its role as the internal classified communications platform, but give no technical detail. Who sourced what is in [sources.md](sources.md#november-2026-reporting). Publication dates for the later reports are not recorded; all had appeared by 17 November 2026.

What it adds up to: [cyberattack versus self-inflicted](assessment.md#cyberattack-versus-self-inflicted).

## 13 November 2026

**Other outages before the NSANet outage (context), 12 to 16 November.**

The NSANet outage followed four other events in five days. They are the subject of the companion repo, [fridaythe13th-cyberattack-or-clusterfuck](https://github.com/shumow/fridaythe13th-cyberattack-or-clusterfuck); the accounts below are from its [chapter 2](https://github.com/shumow/fridaythe13th-cyberattack-or-clusterfuck/blob/main/analysis/chapter-2-the-cluster.md) unless another source is named.

- **Microsoft 365, Thursday 12 to Friday 13 November.** Outlook, Teams and other services were out for about 24 hours, starting on the 12th, not the 13th. Microsoft said there was no indication of malicious activity. Its preliminary post-incident report of 15 November blames a latent defect in its own networking gateway software.
- **FAA nationwide ground stop, Friday 13 November.** About four and a half hours, from about 3:54 pm to about 8:30 pm Eastern. On 14 November the Transportation Secretary and the FAA Administrator said a newly installed router flooded the network during copper-to-fibre maintenance, with no evidence of anything nefarious. The cause is unconfirmed.
- **JPMorgan Chase online banking, Monday 16 November.** Slowed for most of a day. Chase blamed a software bug in on-premise hardware systems and said there was no evidence it was cyber-related. Other banks were affected only where a transaction touched Chase.
- **Optimizely, Monday 16 November.** The one confirmed attack of the week: attacker code was served from 178 organisations' websites through Optimizely's JavaScript, as reported by Report URI and confirmed by Optimizely. It is a web supply-chain compromise and nothing ties it to the outages above.

No source has linked these events. Microsoft said it had no indication the ground stop was related to its outage, and the Homeland Security Secretary said nothing points to the events being connected.

Source type: on-record company and official statements, relayed by journalism, as recorded in the companion repo. That repo lists which pages it opened; they were not re-opened here. The [source check](source-check.md#candidate-sources) separately opened an Al Jazeera report that gives the same Microsoft dates and the same denial, and found the Friday date for the ground stop in The Record and the CNN wire copy.

## 2013

**Prior outage: the NSA's public website went dark.**

The Record cites a 2013 incident in which the NSA's public website went dark; officials attributed it to a scheduled update, and some hackers claimed an attack. The incident is unrelated to the classified network.

Source: The Record. No source type is recorded for this item: a task in [open-questions.md](open-questions.md#needs-sourcing). It is not in the [provenance table](provenance.md#claim-by-claim).

## January 2000

**Prior outage: a crash of nearly three days at Fort Meade.**

CNN's 17 November 2026 report, in the later version of its wire story (read in CBS 58's copy; the early version carried by WRAL has no such paragraph), notes that in 2000 a technical failure at the agency downed computers for nearly three days and interrupted intelligence processing at Fort Meade, per an agency spokesperson at the time. The Record says the outage lasted three days and was put down to a software anomaly and infrastructure problems. That January 2000 crash was widely reported but not publicly tied to NSANet by name.

Source type for CNN's account: journalism citing an on-record official statement. It was the one on-record item in the [provenance table](provenance.md#claim-by-claim) until the NSA's statement of 17 November 2026. The statement that the crash was widely reported names no source yet: a task in [open-questions.md](open-questions.md#needs-sourcing).

## Sources

- CNN, ["Exclusive: Highly classified US national security communications network goes down, sources say"](https://www.cnn.com/2026/11/17/politics/highly-classified-national-security-communications-network-goes-down) † (17 Nov 2026)
- [Forbes](https://www.forbes.com/sites/zacharyfolk/2026/11/17/national-security-agencys-highly-classified-internal-network-has-gone-down-report-says/) †, [The Record](https://therecord.media/nsa-net-disruptions), [ABC News 4](https://abcnews4.com/news/nation-world/nsas-national-security-agency-classified-internal-network-is-down-sources-say-no-evidence-cyberattack-communications), [Ynetnews](https://www.ynetnews.com/article/rkhmwxccgg) coverage of the same outage (17 Nov 2026)
- Wall Street Journal, ["Classified U.S. Intelligence System Is Down for Now, U.S. Officials Say"](https://www.wsj.com/politics/national-security/classified-u-s-intelligence-system-is-down-for-now-u-s-officials-say-aa09b6d1) † (17 Nov 2026), via The Jerusalem Post, ["NSA's highly classified internal communications network shuts down, linked to software update - WSJ"](https://www.jpost.com/international/article-915216) (17 Nov 2026)
- Nextgov/FCW, ["Classified NSA communications network down, people familiar say"](https://www.nextgov.com/digital-government/2026/11/classified-nsa-communications-network-down-people-familiar-say/417277/) (17 Nov 2026)
- New York Times, ["Classified N.S.A. Network Goes Down, Causing Work Disruptions"](https://www.nytimes.com/2026/11/17/us/politics/nsa-down-network-outage-nsanet.html) † (17 Nov 2026), syndicated
- WRAL, ["Highly classified U.S. national security communications network goes down, sources say"](https://www.wral.com/news/local/national-security-communications-network-outage-november-2026/) (17 Nov 2026), carrying the CNN wire story in an early version
- CBS 58, ["Exclusive: Highly classified US national security communications network goes down, sources say"](https://www.cbs58.com/news/exclusive-highly-classified-us-national-security-communications-network-goes-down-sources-say) (17 Nov 2026), carrying the CNN wire story in a later version
- For the outages of 12 to 16 November: the companion repo [fridaythe13th-cyberattack-or-clusterfuck](https://github.com/shumow/fridaythe13th-cyberattack-or-clusterfuck), in particular [chapter 2, the cluster](https://github.com/shumow/fridaythe13th-cyberattack-or-clusterfuck/blob/main/analysis/chapter-2-the-cluster.md), and the sources it records

How far to trust each: [sources.md](sources.md#november-2026-reporting). The full list: [sources.md](sources.md#sources-consulted). † marks a page that refuses automated fetching: its link and title come from search listings or from other pages that cite it, and it was not opened in the [source check](source-check.md).

[Back to README](README.md)
