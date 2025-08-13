---
title: Transfer Learning – Project Portfolio
---

Generalizable models across heterogeneous CRS cohorts (SNOT-22 item scores and related outcomes)

Supervisors: Dr. Sayeed S. Chowdhury · Dr. Snehasis Mukhopadhyay · Dr. Vijay Ramakrishnan  
Student: Yu-Wei Chang  
Affiliations: Purdue University · IU School of Medicine

## Highlights

### Goal
Develop and evaluate transfer learning approaches that perform robustly across datasets collected with slightly different structures but similar clinical targets.

### Near-Term Focus
Data familiarization on SNOT-22 item-level scores (Q1–Q22), missingness analysis, distributions, and correlation structure.

### Validation Plan
Baseline models on US cohorts, cross-cohort validation, and eventual transfer to the German dataset when available.

## Milestones (working list)
- [ ] Familiarization: confirm combined 2R01/3R01 file with Q1–Q22 columns (1–5).
- [ ] EDA: item distributions, per-item missingness, correlation heatmap.
- [ ] Baselines: logistic/forest; metrics + calibration summary.
- [ ] Transfer approach: define feature alignment & evaluation protocol.

_Last updated: {{ site.time | date: "%Y-%m-%d" }}_
