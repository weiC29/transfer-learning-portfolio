---
title: Transfer Learning – Project Portfolio
---

Generalizable models across heterogeneous CRS cohorts (SNOT-22 item scores and related outcomes)

### Supervisors
Dr. Sayeed S. Chowdhury · Dr. Snehasis Mukhopadhyay · Dr. Vijay Ramakrishnan

### Student
Yu-Wei Chang

### Affiliations
Purdue University · IU School of Medicine

## Highlights

### Near-Future Aim (Pipeline)
Stand up a reusable pipeline (data cleaning, feature prep, modeling, evaluation, reporting) that we can run on the US datasets now and apply to the incoming German dataset with minimal changes.

### Long-Term Aim (Common Embeddings)
Develop and evaluate approaches that learn common/transferable embeddings across cohorts collected with slightly different structures but similar clinical targets.

### Current Focus
- Practice on the public **INSPIRE** dataset (PhysioNet) to sharpen process and modeling skills.
- Establish baselines (binary classification) and a clean training/evaluation loop in **PyTorch** (and/or scikit-learn).
- Explore **Siamese neural networks** and other embedding methods for cross-cohort transfer.

## Milestones (working list)
- [ ] INSPIRE data familiarization: schema, targets, feasible prediction tasks.
- [ ] Baseline binary classifier (logistic/forest in scikit-learn; simple MLP in PyTorch).
- [ ] Reusable training/eval pipeline (config-driven, metrics, reproducible seeds).
- [ ] Embedding experiments: Siamese network for similarity/representation learning.
- [ ] Transfer plan draft: how to map features/labels and evaluate cross-cohort performance.

_Last updated: {{ site.time | date: "%Y-%m-%d" }}_
