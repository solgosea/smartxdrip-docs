# Frequently Asked Questions

## Product status

**Is SmartXDrip available now?**
: Not yet. This repository presents the product direction and first planned screens so the community can give feedback before development decisions harden.

**Is this repository the app source code?**
: No. This repository is for public documentation, feature previews, and feedback. It does not currently contain the SmartXDrip application source code.

**Why publish docs before the app is finished?**
: The goal is to validate whether [xDrip+](https://github.com/NightscoutFoundation/xDrip) and [Nightscout](https://nightscout.github.io/) users want this kind of companion review and analysis app, and to learn which features should be included, changed, or delayed.

---

## Relationship to [xDrip+](https://github.com/NightscoutFoundation/xDrip) and [Nightscout](https://nightscout.github.io/)

**Does SmartXDrip replace xDrip+?**
: No. [xDrip+](https://github.com/NightscoutFoundation/xDrip) would remain the tool that receives and manages CGM data on Android. SmartXDrip is planned as a companion review and analysis workspace for that data.

**Does SmartXDrip replace Nightscout?**
: No. [Nightscout](https://nightscout.github.io/) would remain the user-controlled CGM site and sharing layer. SmartXDrip would read from a Nightscout instance that the user configures.

**Will SmartXDrip read CGM sensors directly?**
: No. The planned app would not communicate with CGM sensors directly. It would read data already collected by xDrip+ or Nightscout.

**Will SmartXDrip become my source of truth?**
: No. [xDrip+](https://github.com/NightscoutFoundation/xDrip) or [Nightscout](https://nightscout.github.io/) should remain the source of truth. SmartXDrip is planned as a review layer for data already collected elsewhere.

---

## Planned first features

**Why start with Home, Insights, History, Episode Detail, and Stats?**
: These screens cover the most common review loop: what is happening now, what should I notice, what happened on a specific day, what happened during a high or low event, and what patterns appear across multiple days.

**What is Home?**
: A planned first screen for current glucose, short-term trend, today's Time in Range, and a simple summary. See [Planned Feature: Home](planned-features/home.md).

**What is Insights?**
: A planned review page for daily brief, weekly review, and narrative pattern summaries. See [Insights](features/insights.md).

**What is History?**
: A planned day-by-day review screen for full-day curves and high/low events. See [Planned Feature: History](planned-features/history.md).

**What are High Episode and Low Episode?**
: Focused detail pages opened from History when a sustained high or low event needs more context. See [High Episode](features/high-episode.md) and [Low Episode](features/low-episode.md).

**What is Stats?**
: A planned multi-day summary for Time in Range, average glucose, variability, range breakdown, and visual pattern review. See [Planned Feature: Stats](planned-features/stats.md).

**Will SmartXDrip provide alerts?**
: No. SmartXDrip is not planned to replace existing xDrip+ or Nightscout safety workflows. It is focused on review, analysis, and user-facing summaries.

---

## Privacy and safety

**Will SmartXDrip require an account?**
: The current design goal is no account requirement.

**Will SmartXDrip upload glucose data to its own cloud?**
: The current design goal is local-first storage and no SmartXDrip-operated glucose-data cloud.

**Is SmartXDrip medical advice?**
: No. SmartXDrip is planned as a personal data review tool, not a medical device. It should not be used to make treatment, medication, or dietary decisions without a qualified healthcare provider.

---

## Feedback

**What feedback is most useful right now?**
: Feedback on Home, Insights, History, High/Low Episode, and Stats is the most useful: what feels useful, what feels unnecessary, what is missing, and what would make the app genuinely helpful without duplicating xDrip+ or Nightscout.
