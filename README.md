# SmartXDrip Docs

## Already using [xDrip+](https://github.com/NightscoutFoundation/xDrip) or [Nightscout](https://nightscout.github.io/)?

SmartXDrip is a planned companion app for CGM review and analysis. It is built for people who already rely on [xDrip+](https://github.com/NightscoutFoundation/xDrip) and [Nightscout](https://nightscout.github.io/) as valuable parts of their CGM workflow. It does not replace either project. It focuses on Home, History, and Stats views for the data users already collect.

View the documentation site:

```text
https://solgosea.github.io/smartxdrip-docs/
```

## First planned screens

<table>
  <tr>
    <td align="center"><strong>Home</strong></td>
    <td align="center"><strong>History</strong></td>
    <td align="center"><strong>Stats</strong></td>
  </tr>
  <tr>
    <td><img src="docs/assets/screenshots/home-hero.png" width="220" alt="Home screen preview"></td>
    <td><img src="docs/assets/screenshots/history-hero.png" width="220" alt="History screen preview"></td>
    <td><img src="docs/assets/screenshots/stats-hero.png" width="220" alt="Stats screen preview"></td>
  </tr>
</table>

## Why this exists

[xDrip+](https://github.com/NightscoutFoundation/xDrip) and [Nightscout](https://nightscout.github.io/) have created a strong foundation for CGM users: data collection, device workflows, alerts, uploads, sharing, and user-controlled access to glucose data.

SmartXDrip starts from respect for that foundation. It is exploring a companion workspace for daily status, day-by-day history, multi-day statistics, and user-facing data interpretation.

The goal is to help answer:

- What is happening with my glucose today?
- What happened on a difficult day?
- Are my Time in Range, average glucose, and variability changing?

## Join the discussion

Help shape the first version of SmartXDrip:

- [What would you want to see first when opening a CGM review app?](https://github.com/solgosea/smartxdrip-docs/discussions/1)
- [How do you review a difficult CGM day after it happens?](https://github.com/solgosea/smartxdrip-docs/discussions/2)
- [Which CGM statistics actually help you understand your patterns?](https://github.com/solgosea/smartxdrip-docs/discussions/3)

## What this is not

SmartXDrip is not intended to:

- Replace [xDrip+](https://github.com/NightscoutFoundation/xDrip)
- Replace [Nightscout](https://nightscout.github.io/)
- Read CGM sensors directly
- Replace existing alert and safety workflows
- Make treatment recommendations
- Provide medical advice

SmartXDrip should work alongside the existing tools users already trust, not ask users to move away from them.

## Feedback wanted

The first public review focuses on:

- Whether Home, History, and Stats are the right first screens
- What [xDrip+](https://github.com/NightscoutFoundation/xDrip) users would expect from a review app
- What [Nightscout](https://nightscout.github.io/) users would expect from a review app
- Which details feel useful, confusing, or unnecessary
- Where SmartXDrip should stop so it does not duplicate existing tools

## Repository scope

This repository contains product direction notes, planned feature previews, screenshots, privacy and safety notes, and community feedback material.

This repository does not currently contain the SmartXDrip application source code.

## Local preview

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open:

```text
http://127.0.0.1:8000/smartxdrip-docs/
```

## Medical disclaimer

SmartXDrip is planned as a personal data review tool, not a medical device. It does not provide medical advice. Do not make treatment, medication, or dietary decisions based solely on information shown by the app. Always consult a qualified healthcare provider.
