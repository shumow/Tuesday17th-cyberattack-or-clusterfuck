# Assessment

[README](README.md) · [Provenance](provenance.md) · [Sources](sources.md) · [Timeline](timeline.md) · **Assessment** · [Comparison](comparison.md) · [Open questions](open-questions.md) · [Source check](source-check.md)

What the open evidence adds up to, as of 17 November 2026. This page is assessment, not finding. It rests on the claims in [provenance.md](provenance.md) and the reporting in [timeline.md](timeline.md); statements that do not yet name a source are marked below.

## What "mission critical" means here

- **Supported:** Open sources support the claim that NSANet is the daily working environment for the analytic workforce: internal web, email, wikis, chat, analytic front ends and the secure phone system. They also show it as the back-end destination for TAO-collected data via a DMZ.
- **Not settled:** What open sources do not settle is whether collection and processing pipelines themselves depend on it, or how much has moved to other enclaves since the mid-2000s.
- **Inference:** A plausible reading is that an outage halts analysts' access to tools and communications without necessarily stopping collection, but that is inference, not documented fact.

Related detail is in [sources.md](sources.md): the hosted applications and phone service under [Electrospaces.net](sources.md#electrospacesnet), and the TAO presentation under [Primary documents](sources.md#primary-documents). No source entry names email or chat: a task in [open-questions.md](open-questions.md#needs-sourcing). The unsettled points are tracked in [open-questions.md](open-questions.md#not-settled-by-the-open-evidence).

## Cyberattack versus self-inflicted

The denials are low-information: "no evidence of a cyberattack" on day one describes what has been found, not what has been ruled out. So the question is what would discriminate.

| Profile | What it looks like | Reporting so far |
| --- | --- | --- |
| Botched update | Onset at a maintenance window, uneven service degradation, prior weeks of instability, recovery by rollback within days | Matches this profile on every point available |
| Intrusion | Sudden loss without a change event, data integrity concerns, counter-intelligence involvement, prolonged outage with rebuild | None of these have been reported |

The reporting itself is in the [timeline](timeline.md#17-november-2026).

### Base rate

Every publicly documented compromise of NSA networks was an insider or a leak of unknown vector, not a demonstrated external intrusion of NSANet:

- Snowden (2013, insider). Candidate source: [The Guardian](https://www.theguardian.com/world/2013/jun/09/edward-snowden-nsa-whistleblower-surveillance) †, not opened.
- Harold Martin (arrested 2016, insider). He admitted taking and keeping government documents from about 1996 until his arrest; "hoarding" is his lawyers' description. Source: [NPR](https://www.npr.org/2019/03/28/707742550/former-nsa-contractor-pleads-guilty-to-stealing-classified-information), 28 March 2019, opened.
- The Shadow Brokers release of tools believed to be the NSA's (2016, still publicly unattributed). Source: [TechCrunch](https://techcrunch.com/2026/05/26/ghost-hackers-the-cybersecurity-mystery-that-nobody-has-solved/), 26 May 2026, opened: it says nothing is known about who was behind the group, and has no sentence on how the tools were obtained.

No outside actor has ever been publicly shown inside NSANet.

The Snowden source has not been opened, and the statement that no outside actor has been publicly shown inside NSANet names no source: it is a claim about an absence. Both are tasks in [open-questions.md](open-questions.md#needs-sourcing). † marks a page that refuses automated fetching.

### Where that leaves it

On current evidence the self-inflicted explanation is strongly favoured. This is an assessment, not a finding; a change in the outage's duration or in the agency's posture would be the thing to watch.

Update, later on 17 November 2026: the NSA stated on the record that the outage was a temporary degradation during scheduled routine maintenance, with mission-critical capabilities unaffected (carried by The Record, ABC News 4 and Ynetnews; see the [timeline](timeline.md#17-november-2026)). The Record, from its own sources, describes intermittent service rather than a full shutdown, and the later CNN version and Ynetnews say Five Eyes sharing was unaffected. That fits the self-inflicted explanation, but it is an official account, not independent confirmation, and the reading rule applies to it as to any other.

## Sources

This page rests on the claims in [provenance.md](provenance.md) and the reporting in [timeline.md](timeline.md). Statements that do not yet name a source are marked where they stand. The source list is in [sources.md](sources.md#sources-consulted).

[Back to README](README.md)
