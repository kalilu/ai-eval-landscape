# AI/ML Model Evaluation in Life Sciences — Landscape Analysis

**Author:** Karla Vizcarra Loayza
**Status:** In progress

## Purpose

A structured literature and practice review examining how AI/ML models
are currently evaluated in Life Sciences research contexts (genomics,
proteomics, clinical AI, bioinformatics tools broadly). The goal is to
identify consistent gaps in current practice, particularly around
reproducibility, benchmarking methodology, and deployment readiness,
and consolidate these into a generalizable evaluation framework.

This is independent research, informed by professional experience in
production MLOps and AI/ML model evaluation, but not tied to or
representing any single institution's internal tooling.

## Structure

- `reading-table.md` — source tracking table (target: 25-30 sources)
- `search-log.md` — search methodology, for reproducibility of the
  review itself
- `synthesis.md` — pattern analysis and consolidated gaps
- `guidelines.md` — consolidated findings and community guidelines
  (forthcoming)
- `framework.md` — the proposed evaluation framework: benchmarking
  methodology, reproducibility standards, deployment readiness
  criteria (forthcoming)
- `sources/` — local notes per source

## Method

Structured, table-driven review rather than exhaustive systematic
review. Target: 25-30 sources, prioritising breadth across Life
Sciences sub-domains over depth in any single one. Each source logged
with: what it evaluates, methodology used, and its key limitation
relative to rigorous, reproducible, deployment-ready AI/ML evaluation.

## Roadmap

This repository will expand to include a companion MLOps pipeline
(`mlops-evaluation-pipeline`) implementing the proposed framework —
training, automated evaluation, explainability analysis, and a
deployment-readiness gate — plus an extension applying the framework
to LLM evaluation.
