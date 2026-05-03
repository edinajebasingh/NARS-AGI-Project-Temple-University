 # NARS AGI Project — Temple University 2026

## Stability vs Adaptability in Artificial General Intelligence
### A NARS-Based Experimental Study of Belief Formation Without Large-Scale Training

**Course:** Artificial Intelligence
**University:** Temple University, Philadelphia
**Year:** 2026

---

## Project Overview

This project investigates whether an AI system can build meaningful beliefs 
from scratch with no pre-training and minimal data, and whether those beliefs 
can balance stability and adaptability.

The system used is NARS — Non-Axiomatic Reasoning System — which stores every 
belief as two numbers: frequency (f) and confidence (c).

---

## Files in this Repository

| File | Description |
|------|-------------|
| final_report.pdf | Full 25-page project report |
| AGI_project.ipynb | Google Colab notebook with all experiments |
| nars_experiment_charts.py | Python code that generates all 5 charts |
| presentation.pptx | Project presentation slides |
| chart1_convergence.png | Stage 2 belief convergence chart |
| chart2_contradiction.png | Stage 3 contradiction stress test chart |
| chart3_table.png | Stage 1 cold start belief table |
| chart4_comparison.png | NARS vs GPT comparison chart |
| chart5_inference.png | Stage 1B inference chain diagram |

---

## Experiment Summary

**Stage 1 — Cold Start**
System starts from zero knowledge and forms beliefs immediately from first observation.

**Stage 2 — Reinforcement**
Confirming observations repeated to measure belief stabilisation. Convergence point found at observation 11.

**Stage 3 — Contradiction Stress Test**
Stable beliefs subjected to light, moderate, and heavy contradictions. Belief never reversed — only shifted proportionally.

---

## Key Finding

Stability and adaptability are not opposing forces. A system can build robust 
beliefs from minimal experience and still revise them when evidence demands it.
