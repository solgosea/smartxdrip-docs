# Product Plan

SmartXDrip is a planned companion review app for people who already use [xDrip+](https://github.com/NightscoutFoundation/xDrip) or [Nightscout](https://nightscout.github.io/) to collect CGM data.

The product direction starts with respect for the existing ecosystem. [xDrip+](https://github.com/NightscoutFoundation/xDrip) and [Nightscout](https://nightscout.github.io/) already provide important CGM workflows for data collection, alerts, uploads, sharing, and user-controlled access. SmartXDrip keeps those tools as the source of truth, then adds a companion workspace for daily review, historical patterns, statistics, and user-facing data interpretation.

---

## What SmartXDrip would do

SmartXDrip would read glucose data from:

- **[xDrip+](https://github.com/NightscoutFoundation/xDrip)** on Android through its local Web Service
- **[Nightscout](https://nightscout.github.io/)** through a user-provided URL and readable token

Then it would present that data through:

- A current-day Home view
- A day-by-day History view
- A Stats view for Time in Range, average glucose, variability, and range breakdown

The first public review is intentionally focused. Home, History, and Stats are the starting point, not the final scope. Future features should be added step by step based on community feedback and real user needs.

---

## What SmartXDrip would not do

SmartXDrip is not intended to:

- Read CGM sensors directly
- Replace [xDrip+](https://github.com/NightscoutFoundation/xDrip)
- Replace [Nightscout](https://nightscout.github.io/)
- Replace existing alert and safety workflows
- Upload glucose data to a SmartXDrip cloud
- Make treatment decisions
- Provide medical advice

---

## Intended users

SmartXDrip is mainly for:

- [xDrip+](https://github.com/NightscoutFoundation/xDrip) users who want a dedicated daily review view
- [Nightscout](https://nightscout.github.io/) users who want an additional way to revisit patterns
- parents, partners, and self-trackers who already rely on existing CGM data flows
- people who want summaries without moving away from their current setup

The project should be careful not to add another required service or another source of truth.

The relationship should be additive: SmartXDrip should help users work with the CGM data they already collect, while preserving the role of the tools and communities they already rely on.

---

## First planned features

| Feature | Purpose | Feedback needed |
|---|---|---|
| [Home](planned-features/home.md) | Show the current glucose state clearly | Is the first screen useful at a glance? |
| [History](planned-features/history.md) | Review one day at a time | Does the daily review match how users think about CGM data? |
| [Stats](planned-features/stats.md) | Summarize 7-90 day patterns | Are the metrics and charts understandable? |

---

## Community questions

The main questions for the first public review are:

- Would xDrip+ or Nightscout users want this companion analysis workspace?
- Are Home, History, and Stats the right starting point?
- Which details should be removed to keep the app simple?
- Which details are missing for real daily use?
- Should the app be Android-first, Nightscout-first, or support both from the start?
- Where should SmartXDrip stop so it does not become a replacement for existing tools?

---

## Current status

SmartXDrip is in the product-design and community-feedback stage. The screenshots shown in this documentation represent planned screens and may change before implementation.
