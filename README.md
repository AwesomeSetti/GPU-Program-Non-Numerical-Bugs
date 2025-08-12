# GPU-Program-Non-Numerical-Bugs
A comprehensive study on non-numerical bugs in tile-based GPU programming models
# Comprehensive Study on GPU Program Non-Numerical Issues

This repository contains a curated dataset and analysis of **non-numerical bugs** found in tile-based GPU programming models (e.g., Triton, CUTLASS, TVM, PlaidML, NVIDIA Warp).

Contents
- `non_numerical_bugs.csv` – Master spreadsheet of categorized non-numerical bugs  
- `scripts/` – (Optional) Scripts to parse, analyze, and visualize bug data  
- `docs/` – Documentation, methodology, and references
- 
 Data Columns
| Column | Description |
|--------|-------------|
| Project | Name of the GPU project/library |
| Repo Stars | GitHub star count at collection time |
| Contributors | Total contributors |
| Bug Title | GitHub issue title |
| Bug Link | Direct link to issue |
| Component | Affected area (Install/Build, API, Memory, Concurrency, Performance, etc.) |
| Root Cause | Summary of cause |
| Symptom | High-level bug symptom |
| Symptom Subcategory | Detailed classification |
| Fixing Strategy | How the bug was resolved |
| Description | Summary of the bug and fix |

 Methodology
Bugs were collected from open-source repositories by:
1. Filtering issues related to tile-based GPU programming.
2. Excluding numerical bugs (precision, NaN, etc.).
3. Classifying based on affected component, root cause, and fix strategy.

 License
[MIT License](LICENSE)

---
Inspired by: [Comprehensive Study on GPU Program Numerical Issues](https://github.com/GPU-Program-Bug-Study/Comprehensive-Study-on-GPU-Program-Numerical-Issues.github.io/tree/main/GPU-NBDetect)
