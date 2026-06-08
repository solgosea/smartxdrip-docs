# Product Plan

SmartXDrip is a planned companion app for people who already use xDrip+ or Nightscout to collect CGM data.

The product direction is simple: keep xDrip+ and Nightscout as the data sources, then add a calmer analysis layer that makes glucose history easier to read.

---

## What SmartXDrip would do

SmartXDrip would read glucose data from:

- **xDrip+** on Android through its local Web Service
- **Nightscout** through a user-provided URL and readable token

Then it would present that data through:

- A current-day Home view
- A day-by-day History view
- A Stats view for Time in Range, average glucose, variability, and range breakdown

The first version is intentionally small. The goal is to validate whether these three views solve a real need before expanding into deeper analysis.

---

## What SmartXDrip would not do

SmartXDrip is not intended to:

- Read CGM sensors directly
- Replace xDrip+
- Replace Nightscout
- Upload glucose data to a SmartXDrip cloud
- Make treatment decisions
- Provide medical advice

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

- Would xDrip+ or Nightscout users want this extra analysis layer?
- Are Home, History, and Stats the right first three features?
- Which details should be removed to keep the app simple?
- Which details are missing for real daily use?
- Should the app be Android-first, Nightscout-first, or support both from the start?

---

## Current status

SmartXDrip is in the product-design and community-feedback stage. The screenshots shown in this documentation represent planned screens and may change before implementation.
