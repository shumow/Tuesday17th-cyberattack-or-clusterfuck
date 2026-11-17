# Assessment

[README](README.md) · [Provenance](provenance.md) · [Sources](sources.md) · [Timeline](timeline.md) · **Assessment** · [Comparison](comparison.md) · [Open questions](open-questions.md)

What the open evidence adds up to, as of 17 November 2026. This page is assessment, not finding. The claims it rests on are in [provenance.md](provenance.md).

## What "mission critical" means here

- **Supported:** Open sources support the claim that NSANet is the daily working environment for the analytic workforce: internal web, email, wikis, chat, analytic front ends and the secure phone system. They also show it as the back-end destination for TAO-collected data via a DMZ.
- **Not settled:** What open sources do not settle is whether collection and processing pipelines themselves depend on it, or how much has moved to other enclaves since the mid-2000s.
- **Inference:** A plausible reading is that an outage halts analysts' access to tools and communications without necessarily stopping collection, but that is inference, not documented fact.

The detail behind the first point is in [sources.md](sources.md): the hosted applications and phone service under [Electrospaces.net](sources.md#electrospacesnet), and the TAO presentation under [Primary documents](sources.md#primary-documents). The unsettled points are tracked in [open-questions.md](open-questions.md#not-settled-by-the-open-evidence).

## Cyberattack versus self-inflicted

The denials are low-information: "no evidence of a cyberattack" on day one describes what has been found, not what has been ruled out. So the question is what would discriminate.

| Profile | What it looks like | Reporting so far |
| --- | --- | --- |
| Botched update | Onset at a maintenance window, uneven service degradation, prior weeks of instability, recovery by rollback within days | Matches this profile on every point available |
| Intrusion | Sudden loss without a change event, data integrity concerns, counter-intelligence involvement, prolonged outage with rebuild | None of these have been reported |

The reporting itself is in the [timeline](timeline.md#17-november-2026).

### Base rate

Every publicly documented compromise of NSA networks was an insider or a leak of unknown vector, not a demonstrated external intrusion of NSANet:

- Snowden (2013, insider)
- Harold Martin (2016, insider hoarding)
- The Shadow Brokers release of TAO tooling (2016, vector still publicly unattributed)

No outside actor has ever been publicly shown inside NSANet.

These cases do not yet name a source. That is a task in [open-questions.md](open-questions.md#needs-sourcing).

### Where that leaves it

On current evidence the self-inflicted explanation is strongly favoured. This is an assessment, not a finding; a change in the outage's duration or in the agency's posture would be the thing to watch.

## Sources

This page rests on the claims in [provenance.md](provenance.md) and the reporting in [timeline.md](timeline.md). The source list is in [sources.md](sources.md#sources-consulted).

[Back to README](README.md)
