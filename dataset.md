# Dataset Versions and Code

The USASSA data is provided at the country-year level to facilitate seamless merging with standard political science and econometric panels[cite: 1].

## Version 2.0 (Active)
**Coverage: 2000 – May 2026**

This major update expands the dataset utilizing primary disbursement data from ForeignAssistance.gov. The coding protocol integrates AI-assisted algorithmic classification mapped to the original typologies, followed by rigorous manual verification by the research team.

*   [USASSA_v2_Country_Year.csv](link) - The primary analysis dataset.
*   [USASSA_v2_RAW_LineItems.csv](link) - The unaggregated, raw line-item data preserving the original text fields and the binary `out_of_scope` exclusion flags.
*   [Codebook_v2.pdf](link) - Comprehensive variable definitions and methodology.
*   [Replication_Script.do](link) - Stata script for generating composite `lethal` and `nonlethal` variables[cite: 1].

## Version 1.0 (Archived)
**Coverage: 2000 – 2019**

The foundational dataset compiled in collaboration with the Security Assistance Monitor (SAM)[cite: 1].

*   [USASSA_v1_Country_Year.csv](link)
*   [USASSA_v1_Codebook.pdf](link)

## Methodology Overview
![Methodology Flowchart](assets/methodology.png)

To protect empirical comparisons from modeling noise, the dataset implements composite transformations:
*   **Lethal Aid:** Merges material support, military training, and coordinated train-and-equip authorities[cite: 1].
*   **Nonlethal Aid:** Aggregates security sector education, structural reform, humanitarian security interventions, and counterproliferation[cite: 1].
