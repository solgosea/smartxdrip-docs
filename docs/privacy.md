# Privacy & Safety Direction

This page describes the intended privacy and safety direction for SmartXDrip. The app is still planned, so details may change as implementation begins.

---

## Privacy goals

SmartXDrip is intended to be local-first.

The current design goals are:

- No required account
- No SmartXDrip-operated glucose-data cloud
- No advertising or analytics SDKs
- Local storage for glucose readings
- User-controlled data sources
- Read-only access to xDrip+ or Nightscout data

---

## Planned data sources

SmartXDrip is planned to read from:

- **xDrip+ local Web Service** on Android
- **Nightscout** through a user-provided URL and readable token

SmartXDrip is not planned to read CGM sensors directly.

---

## Data handling direction

The intended model is:

- xDrip+ or Nightscout collects the CGM data
- SmartXDrip reads the data for review and analysis
- SmartXDrip stores app data locally on the user's device
- SmartXDrip does not write treatment decisions back to the source system

If implementation requires any change to this model, the documentation should be updated clearly before release.

---

## Medical boundary

SmartXDrip is planned as a personal data review tool, not a medical device.

It should not:

- Diagnose conditions
- Recommend insulin or medication dosing
- Replace CGM alerts
- Replace clinical guidance
- Be used as the only basis for treatment decisions

Always consult a qualified healthcare provider before making treatment, medication, or dietary decisions.
