# SmartXDrip Docs

This repository hosts the public product plan, feature previews, and community feedback space for SmartXDrip.

View the documentation site:

```text
https://solgosea.github.io/smartxdrip-docs/
```

SmartXDrip is a planned companion review app for people who already use xDrip+ or Nightscout. It does not replace either project. It keeps xDrip+ and Nightscout as the data sources and focuses on calmer daily review, history, and statistics.

## Repository scope

This repository contains:

- Product direction notes
- Planned feature previews
- Screenshots and mockups
- Privacy and safety notes
- Community feedback material

This repository does not currently contain the SmartXDrip application source code.

## First public batch

The first documentation batch focuses on the planned MVP:

- Home
- History
- Stats
- xDrip+ and Nightscout as the source of truth
- Privacy and medical-safety boundaries

## Product boundaries

SmartXDrip is not intended to:

- Replace xDrip+
- Replace Nightscout
- Read CGM sensors directly
- Act as an alerting system
- Make treatment recommendations
- Provide medical advice

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
