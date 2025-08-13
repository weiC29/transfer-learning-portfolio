<div class="hero">
  <h1>Transfer Learning for Clinical Decision-Making</h1>
  <p class="sub">Generalizable models across heterogeneous CRS cohorts (SNOT-22 item scores and related outcomes)</p>
  <div class="badges">
    <span class="badge">Supervisors: Dr. Sayeed S. Chowdhury • Dr. Snehasis Mukhopadhyay • Dr. Vijay Ramakrishnan</span>
    <span class="badge">Student: Yu-Wei Chang</span>
  </div>
</div>

## Highlights
<div class="grid">
  <div class="card">
    <h3>Goal</h3>
    <p>Develop and evaluate transfer learning approaches that perform robustly across datasets collected with slightly different structures but similar clinical targets.</p>
  </div>
  <div class="card">
    <h3>Near-Term Focus</h3>
    <p>Data familiarization on SNOT-22 item-level scores (Q1–Q22), missingness analysis, distributions, and correlation structure.</p>
  </div>
  <div class="card">
    <h3>Validation Plan</h3>
    <p>Baseline models on US cohorts, cross-cohort validation, and eventual transfer to the German dataset when available.</p>
  </div>
</div>

## Milestones (working list)
- [ ] Familiarization: confirm combined 2R01/3R01 file with Q1–Q22 columns (1–5).
- [ ] EDA: item distributions, per-item missingness, correlation heatmap.
- [ ] Baselines: logistic/forest; metrics + calibration summary.
- [ ] Transfer approach: define feature alignment & evaluation protocol.

_Updated: {{ site.time | date: "%Y-%m-%d" }}_
