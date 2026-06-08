# SmartXDrip Docs

## Already using [xDrip+](https://github.com/NightscoutFoundation/xDrip) or [Nightscout](https://nightscout.github.io/)?

SmartXDrip is a planned companion app for reviewing CGM data more clearly. It does not replace [xDrip+](https://github.com/NightscoutFoundation/xDrip) or [Nightscout](https://nightscout.github.io/). It focuses on Home, History, and Stats views for the data you already collect.

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

[xDrip+](https://github.com/NightscoutFoundation/xDrip) and [Nightscout](https://nightscout.github.io/) are powerful parts of the CGM ecosystem. SmartXDrip is exploring whether users also need a calmer review layer for daily status, day-by-day history, and multi-day statistics.

The goal is to help answer:

- What is happening with my glucose today?
- What happened on a difficult day?
- Are my Time in Range, average glucose, and variability changing?

## What this is not

SmartXDrip is not intended to:

- Replace [xDrip+](https://github.com/NightscoutFoundation/xDrip)
- Replace [Nightscout](https://nightscout.github.io/)
- Read CGM sensors directly
- Act as an alerting system
- Make treatment recommendations
- Provide medical advice

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
