# Computational Thinking Course GitHub Analytics (2018-2025)

Analysis of student engagement in the [Computational Thinking and Programming course](https://www.unibo.it/en/study/phd-professional-masters-specialisation-schools-and-other-programmes/course-unit-catalogue/course-unit/2024/467045) through [GitHub data](https://github.com/comp-think) across different academic cohorts (2018-2025) at the University of Bologna's Digital Humanities and Digital Knowledge master's program.

This repository is part of my master's thesis project at the Digital Humanities and Digital Knowledge program, focusing on analyzing student engagement patterns to evaluate and improve interactive learning frameworks in programming education.


## Repository Structure
.
├── github_stats.ipynb    # Analysis notebook
├── repo_data/           # Raw GitHub data by cohort
│   ├── 2018-2019.csv
│   ├── 2019-2020.csv
│   └── ...
└── README.md


## Analysis Overview

The script analyzes GitHub engagement data across different academic cohorts:

1. **Cohort Statistics**
   - Number of unique users per academic year
   - Distribution of student engagement

2. **Engagement Metrics**
   - Average comments/tasks per user
   - Task completion distributions
   - Engagement patterns across cohorts

## Key Findings

The distribution of solved tasks per student across different cohorts shows interesting patterns:

![Task Distribution Boxplot](figures/task_distribution_boxplot.png)

This visualization reveals:
- Consistent median task completion across years
- Varying levels of engagement between cohorts
- Presence of highly engaged outliers in some years

