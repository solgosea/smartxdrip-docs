# Privacy & Safety Direction

This page describes the intended privacy and safety direction for SmartXDrip. The app is still planned, so details may change as implementation begins.

---

## Privacy goals

SmartXDrip is intended to be local-first.

The current design goals are:

- No required account
- No SmartXDrip-operated glucose-data cloud
- No advertising or analytics SDKs inside the SmartXDrip app
- Local storage for glucose readings
- User-controlled data sources
- Read-only access to [xDrip+](https://github.com/NightscoutFoundation/xDrip) or [Nightscout](https://nightscout.github.io/) data
- [xDrip+](https://github.com/NightscoutFoundation/xDrip) or [Nightscout](https://nightscout.github.io/) remaining the source of truth

---

## Planned data sources

SmartXDrip is planned to read from:

- **[xDrip+](https://github.com/NightscoutFoundation/xDrip) local Web Service** on Android
- **[Nightscout](https://nightscout.github.io/)** through a user-provided URL and readable token

SmartXDrip is not planned to read CGM sensors directly.

---

## Data handling direction

The intended model is:

- [xDrip+](https://github.com/NightscoutFoundation/xDrip) or [Nightscout](https://nightscout.github.io/) collects the CGM data
- SmartXDrip reads the data for review and analysis
- SmartXDrip stores app data locally on the user's device
- SmartXDrip does not write treatment decisions back to the source system
- SmartXDrip does not replace the safety workflows users already rely on

If implementation requires any change to this model, the documentation should be updated clearly before release.

---

## Website analytics

This documentation website uses Baidu Tongji to understand page visits and traffic sources. The purpose is to learn which public documentation pages are useful to the community and improve future docs and feedback discussions.

This website analytics script is separate from the planned SmartXDrip app. It does not mean the app will include advertising or analytics SDKs.

---

## Medical boundary

SmartXDrip is planned as a personal data review tool, not a medical device.

It should not:

- Diagnose conditions
- Recommend insulin or medication dosing
- Replace CGM alerts
- Become the source of truth for CGM readings
- Replace clinical guidance
- Be used as the only basis for treatment decisions

Always consult a qualified healthcare provider before making treatment, medication, or dietary decisions.
