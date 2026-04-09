# Southeast Asia's SDG Progression through Markovian Correlations

> Modeling the transition dynamics of SDG achievement across Southeast Asian nations
> using Markov chain analysis.


**Course:** Computer Simulation and Modeling| **Date:** May 2024
**Authors:** Rasheed Albel, Val Elagonde, Franz Layug, Christian Paraan

---

## Overview

The United Nations' Sustainable Development Goals (SDGs) represent a global
framework for measuring development progress. This project applies **Markov chain
modeling** to analyze and predict how Southeast Asian countries transition between
SDG performance states over time — providing a probabilistic lens on regional
development trajectories.

By treating each country's SDG score as a state in a Markov process, we estimate
**transition probability matrices** that capture how likely a nation is to improve,
maintain, or regress in its SDG performance from one period to the next.

---

## Research Questions

- How do Southeast Asian countries transition between SDG performance levels over time?
- Which SDG indicators are most correlated with state transitions?
- Can Markovian models predict future SDG trajectories for the region?

---

## Data

- **Source:** UN SDG Indicator Database / Sustainable Development Report
- **Coverage:** Southeast Asian nations (ASEAN member states)
- **Time Period:** Multi-year panel data on SDG indicators
- **Key Variables:** SDG scores across 17 goals, country-year observations

---

## Methodology

### Markov Chain Framework

1. **State Definition** — Countries are discretized into SDG performance states
   (e.g., Low, Medium, High) based on composite SDG index scores
2. **Transition Matrix Estimation** — Empirical transition probabilities are
   computed from observed year-over-year state changes
3. **Steady-State Analysis** — Long-run equilibrium distributions are derived
   to project where the region is headed
4. **Correlation Analysis** — SDG indicators are correlated with transition
   probabilities to identify key drivers of progression

### Steps
- Data cleaning and normalization of SDG indicators
- State discretization using quantile-based binning
- Estimation of transition probability matrices per country/region
- Stationary distribution computation
- Visualization of transition dynamics

---

## Key Findings

- Transition probabilities reveal asymmetric development paths — countries
  that improve tend to continue improving (persistence effects)
- Certain SDG goals (e.g., SDG 3: Good Health, SDG 4: Quality Education)
  show stronger correlations with upward state transitions
- Steady-state distributions suggest the region is converging toward medium-high
  SDG performance over the long run, though with significant cross-country variance

---

## Tech Stack

`Python` · `NumPy` · `Pandas` · `Matplotlib` · `Seaborn` · `SciPy`

---

## References 

[1] “Asia and the Pacific SDG progress report 2024 : showcasing transformative actions,” ESCAP. https://www.unescap.org/kp/2024/asia-and-pacific-sdg-progress-report-2024#

[2] “Asia and the Pacific SDG progress report 2022 : widening disparities amid COVID-19,” ESCAP. https://www.unescap.org/kp/2022/asia-and-pacific-sdg-progress-report-2022

[3] “Asia and the Pacific SDG progress report 2023 : championing sustainability despite adversities,” ESCAP. https://www.unescap.org/kp/2023/asia-and-pacific-sdg-progress-report-2023

[4] “Asia and the Pacific SDG progress report 2021,” ESCAP. https://www.unescap.org/kp/2021/asia-and-pacific-sdg-progress-report-2021

[5] “Asia and the Pacific SDG progress report 2020,” ESCAP. https://www.unescap.org/publications/asia-and-pacific-sdg-progress-report-2020

[6] “Asia and the Pacific SDG progress report 2019,” ESCAP. https://www.unescap.org/publications/asia-and-pacific-sdg-progress-report-2019

[7] “Asia and the Pacific SDG progress report 2017,” ESCAP. https://www.unescap.org/publications/asia-and-pacific-sdg-progress-report-2017

[8] A. K. Jain and S. N. Mishra, “Role of NITI AAYOG in the implementation of the 2030 Agenda,” in South Asia economic and policy studies, 2019, pp. 239–254. doi: 10.1007/978-981-32-9091-4_11.

[9] S. Pakkan, C. Sudhakar, S. Tripathi, and M. Rao, “A correlation study of Sustainable Development Goal (SDG) interactions,” Research Square (Research Square), Nov. 2021, doi: 10.21203/rs.3.rs-779385/v1.

[10] F. G. Renaud, X. Zhou, L. S. Bosher, B. Barrett, and S. Huang, “Synergies and trade-offs between sustainable development goals and targets: innovative approaches and new perspectives,” Sustainability Science, vol. 17, no. 4, pp. 1317–1322, Jul. 2022, doi: 10.1007/s11625-022-01209-9. 

---

## Acknowledgment of Tools

AI tools (e.g., ChatGPT) were used selectively to support code debugging and structure refinement; all analytical design, methodology selection, and interpretation were completed independently.

---

## Individual Contributions

This was a collaborative project completed as part of CSCi 115.

My primary contributions included:
- Writing the research introduction and review of related literature, contextualizing SDG progress in Southeast Asia and the Asia-Pacific region
- Synthesizing policy-oriented motivation linking SDG interdependencies with regional development strategy
- Supporting correlation-based analysis of interrelationships among SDG indicators
- Contributing to the interpretation of transition dynamics and regional development implications
- Preparing technical presentation materials summarizing research objectives, methodology, and findings
