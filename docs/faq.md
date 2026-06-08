# Frequently Asked Questions

## Product status

**Is SmartXDrip available now?**
: Not yet. This repository presents the product direction and first planned screens so the community can give feedback before development decisions harden.

**Is this repository the app source code?**
: No. This repository is for public documentation, feature previews, and feedback. It does not currently contain the SmartXDrip application source code.

**Why publish docs before the app is finished?**
: The goal is to validate whether xDrip+ and Nightscout users actually want this kind of companion app, and to learn which features should be simplified, changed, or delayed.

---

## Relationship to xDrip+ and Nightscout

**Does SmartXDrip replace xDrip+?**
: No. xDrip+ would remain the tool that receives and manages CGM data on Android. SmartXDrip is planned as a clearer review and analysis layer on top of that data.

**Does SmartXDrip replace Nightscout?**
: No. Nightscout would remain a user-controlled data source. SmartXDrip would read from a Nightscout instance that the user configures.

**Will SmartXDrip read CGM sensors directly?**
: No. The planned app would not communicate with CGM sensors directly. It would read data already collected by xDrip+ or Nightscout.

---

## Planned first features

**Why start with Home, History, and Stats?**
: These three screens cover the most common review loop: what is happening now, what happened on a specific day, and what patterns appear across multiple days.

**What is Home?**
: A planned first screen for current glucose, short-term trend, today's Time in Range, and a simple summary. See [Planned Feature: Home](planned-features/home.md).

**What is History?**
: A planned day-by-day review screen for full-day curves and high/low events. See [Planned Feature: History](planned-features/history.md).

**What is Stats?**
: A planned multi-day summary for Time in Range, average glucose, variability, range breakdown, and visual pattern review. See [Planned Feature: Stats](planned-features/stats.md).

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
: Feedback on the planned Home, History, and Stats screens is the most useful: what feels clear, what feels unnecessary, what is missing, and what would make the app genuinely helpful for xDrip+ or Nightscout users.
