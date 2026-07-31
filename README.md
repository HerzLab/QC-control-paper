# iEEG Session-Level QC Pipeline

## Overview
This repository contains a modular quality control (QC) framework for intracranial EEG (iEEG) experiments involving cognitive tasks and direct electrical stimulation.

The pipeline integrates:
- Electrophysiological recordings
- Behavioral event logs
- Stimulation metadata

to generate automated session-level QC reports for rapid review and reproducible preprocessing.

## Goals of the QC Framework

The pipeline is designed to:

- Detect protocol deviations and synchronization failures
- Verify stimulation timing and delivery parameters
- Identify noisy or unstable recording channels
- Summarize behavioral task integrity
- Generate reproducible session-level QC documentation
- Support harmonized preprocessing across sites and experiments

---

# Important Notes

This pipeline:
- Does NOT replace expert review
- Does NOT automatically exclude channels
- Does NOT diagnose epileptiform activity

---

# Customization

The framework is modular.
Behavioral summaries, thresholds, and QC metrics should be adapted to the experimental paradigm and analysis goals.

---

# Citation
> *[Insert manuscript citation once available]*

---
