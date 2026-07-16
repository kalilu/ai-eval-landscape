# Reading Table — AI/ML Model Evaluation in Life Sciences

Target: 25–30 sources by end of Week 2, Day 8.
Fill incrementally. Don't aim for perfect summaries on first pass —
skim first, batch-read second (see search-log.md for daily targets).

| # | Source (Author, Year, Title) | Domain | What it evaluates | Methodology | Key limitation | Link |
|---|---|---|---|---|---|---|
| 1 | Lewis et al. 2025, "Scalable emulation of protein equilibrium ensembles with generative deep learning" (BioEmu), Science | Proteomics | A generative model (BioEmu) that predicts protein conformational ensembles and stability, built on AlphaFold's sequence-structure representations + diffusion model | Multi-task benchmarking: compared against baselines (AFCluster, AlphaFlow, DiG) on curated experimentally-validated test sets; validated against MD simulation ground truth and experimental stability measurements (MEGAscale); reports MAE, Spearman correlation, coverage % per task | Evaluation is benchmark-specific and task-siloed (domain motions, unfolding, pockets, stability each scored separately with different metrics/thresholds) — no single unified "is this model ready for use" criterion; also explicitly out-of-scope: membrane environments, ligands, multi-chain complexes not evaluated at all, and authors flag no confidence/uncertainty module exists (unlike AlphaFold) | https://doi.org/10.1126/science.adv9817 |
| 2 | | | | | | |
| 3 | | | | | | |
| 4 | | | | | | |
| 5 | | | | | | |
| 6 | | | | | | |
| 7 | | | | | | |
| 8 | | | | | | |
| 9 | | | | | | |
| 10 | | | | | | |
| 11 | | | | | | |
| 12 | | | | | | |
| 13 | | | | | | |
| 14 | | | | | | |
| 15 | | | | | | |
| 16 | | | | | | |
| 17 | | | | | | |
| 18 | | | | | | |
| 19 | | | | | | |
| 20 | | | | | | |
| 21 | | | | | | |
| 22 | | | | | | |
| 23 | | | | | | |
| 24 | | | | | | |
| 25 | | | | | | |
| 26 | | | | | | |
| 27 | | | | | | |
| 28 | | | | | | |
| 29 | | | | | | |
| 30 | | | | | | |

## Domain legend (use consistently in the Domain column)
- Genomics
- Proteomics
- Clinical AI / diagnostics
- Bioinformatics tools (general)
- Cross-domain / methodology papers (not tied to one sub-domain)

## Column guidance
- **What it evaluates**: the object of evaluation — a specific model type,
  a benchmark, a tool, a platform capability
- **Methodology**: how they evaluate — accuracy metrics only? Reproducibility
  checks? Human review? Automated pipeline?
- **Key limitation**: the ONE thing this source doesn't address that matters
  for a generalizable, reproducible, deployment-ready framework. Be specific,
  not generic ("lacks reproducibility checks" not "not comprehensive")
