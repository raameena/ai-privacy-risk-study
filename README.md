# AI Privacy Risk & User Behavior Study

A survey-based research project examining whether users understand AI privacy risks, whether they feel at risk, and whether that awareness actually changes their behavior — published as an IEEE-format conference paper.

[Read the full report](report/IEEE_Final_Report.pdf)

## Overview

AI assistants are widely used despite limited user understanding of how they handle sensitive data. This study surveyed users on their AI usage habits, knowledge of data practices, trust levels, and risk-taking behavior, then tested whether a short educational intervention could close the gap between what users *know* and what they *do*.

## Key Findings

- Identified an **awareness-to-action gap**: users reported low trust in AI systems but still shared sensitive information with them.
- **63%** of frequent AI users shared at least one type of sensitive information, despite **62.5%** reporting low trust in AI.
- **55%** of frequent AI users had uploaded personal documents (resumes, IDs, etc.) to an AI system at least once.
- A brief educational intervention produced a statistically significant improvement in verification behavior for both AI-generated text (p = 0.0157) and links (p = 0.0003).
- Found that even low-effort education can measurably shift users toward safer AI-use habits.

## Methods

- Survey design and distribution (21 questions across demographics, usage, knowledge, behavior, and trust)
- Descriptive statistics
- Chi-square tests of independence
- Wilcoxon signed-rank tests (paired pre-/post-intervention comparison)
- Data visualization

## Tools

R · R Markdown · ggplot2 · dplyr · tidyr · Qualtrics · LaTeX

## My Contributions

This was a 5-author paper. My specific contributions:

- Survey development and question formation
- Led data analysis: trust, risk perception, sensitive data-sharing behavior, and education intervention impact
- Conducted statistical testing (Chi-square, Wilcoxon signed-rank) to evaluate relationships between AI usage, trust, and behavior
- Wrote the Data Analysis section of the final paper

## Repository Structure

```text
ai-privacy-risk-study/
├── README.md
├── report/
│   ├── IEEE_Final_Report.pdf
│   └── Data_Analysis_and_Findings.pdf
└── analysis/
    └── Analysis.Rmd
```

## Reproducing the Analysis

Raw survey responses are not included in this repository to preserve participant anonymity, consistent with the study's data collection terms. `analysis/Analysis.Rmd` contains the full statistical workflow (Chi-square tests, Wilcoxon signed-rank tests, and all visualizations) and can be adapted to run against a similarly structured dataset.
