# SmartXDrip

<div class="sx-hero" markdown>

<div class="sx-hero-eyebrow">FOR XDRIP+ · NIGHTSCOUT · COMMUNITY REVIEW</div>

# A companion review app for xDrip+ and Nightscout users.

<p class="sx-hero-sub">
SmartXDrip is being designed for people who already collect CGM data with xDrip+ or Nightscout. It does not replace either project. It keeps them as the source of truth and adds a calmer way to review daily status, history, and statistics.
</p>

<div class="sx-hero-actions" markdown>
[View product plan](product-plan.md){ .md-button .md-button--primary }
[Preview features](planned-features/home.md){ .md-button }
</div>

<div class="sx-stats">
  <div class="sx-stat">
    <div class="sx-stat-value">xDrip+</div>
    <div class="sx-stat-label">Android data source</div>
  </div>
  <div class="sx-stat">
    <div class="sx-stat-value">Nightscout</div>
    <div class="sx-stat-label">Cloud/self-hosted source</div>
  </div>
  <div class="sx-stat">
    <div class="sx-stat-value">3</div>
    <div class="sx-stat-label">First planned features</div>
  </div>
  <div class="sx-stat">
    <div class="sx-stat-value">Feedback</div>
    <div class="sx-stat-label">Before development hardens</div>
  </div>
</div>

</div>

---

<span class="sx-eyebrow">What this is</span>

## For people already using xDrip+ or Nightscout

SmartXDrip is planned as a companion review layer on top of CGM data already collected by xDrip+ or Nightscout.

It may be useful if you:

- use xDrip+ as your Android CGM hub
- use Nightscout as your personal or family CGM data site
- want a quieter daily review screen instead of another alerting tool
- care about Time in Range, history, variability, and recurring patterns
- want xDrip+ or Nightscout to remain the source of truth

The app would help users answer everyday questions:

- What is happening with my glucose right now?
- How did today compare with recent days?
- Which days or time windows are repeatedly difficult?
- Are my Time in Range, average glucose, and variability improving?

SmartXDrip would not read CGM sensors directly, replace xDrip+, replace Nightscout, act as an alerting system, or provide medical advice.

---

<span class="sx-eyebrow">First planned release</span>

## Planned features

<div class="sx-feature-grid" markdown>

<div class="sx-feature" markdown>
<div class="sx-feature-icon">01 · HOME</div>
<div class="sx-feature-title">Current glucose overview</div>
<p class="sx-feature-desc">A focused first screen for the latest reading, short-term trend, today's Time in Range, and one plain-language summary.</p>
<a class="sx-feature-link" href="planned-features/home/">Preview Home</a>
</div>

<div class="sx-feature" markdown>
<div class="sx-feature-icon">02 · HISTORY</div>
<div class="sx-feature-title">Day-by-day review</div>
<p class="sx-feature-desc">A daily timeline for reviewing glucose curves, high/low events, and what happened on a specific day.</p>
<a class="sx-feature-link" href="planned-features/history/">Preview History</a>
</div>

<div class="sx-feature" markdown>
<div class="sx-feature-icon">03 · STATS</div>
<div class="sx-feature-title">Readable statistics</div>
<p class="sx-feature-desc">Time in Range, average glucose, variability, range breakdown, and visual summaries across 7 to 90 days.</p>
<a class="sx-feature-link" href="planned-features/stats/">Preview Stats</a>
</div>

</div>

---

## Why publish this now?

This repository is being published before the product is finalized so CGM users can react to the direction early.

The most useful feedback right now is:

- Whether Home / History / Stats are the right first features
- Whether the screenshots show information in a useful order
- Whether xDrip+ and Nightscout users expect a different review workflow
- Which terms are confusing for non-clinical users
- What safety language should be made clearer
 
---

## Respecting the existing ecosystem

SmartXDrip should fit into the xDrip+ and Nightscout ecosystem without competing with the tools users already rely on.

- xDrip+ remains the Android data hub and sensor-facing tool.
- Nightscout remains the user-controlled CGM site and sharing layer.
- SmartXDrip focuses only on review, interpretation, and feedback-friendly summaries.

---

!!! warning "Medical disclaimer"
    SmartXDrip is planned as a personal data review tool, not a medical device.
    Nothing in this app should be treated as medical advice. Do not make treatment,
    medication, or dietary decisions based solely on what the app shows.
    Always consult your healthcare provider.
