---
title: "Multi-Day Horizon Solar Power Forecasting"
collection: publications
category: conferences
permalink: /publication/2026-10-12-NAPS-solar
excerpt: 'This paper proposes the Systematic Pre-Modeling Optimization Framework (SPOF), a three-step pre-processing pipeline for solar photovoltaic (PV) forecasting, and shows that pre-processing improves accuracy about twice as much as choosing a better algorithm across eight models from four families.'
date: 2026-09-15
venue: '2026 North American Power Symposium (NAPS)'
citation: 'Chowdhury, M. R., Imam, T., Mamun, M. A., Sifat, A. I. & Ferdaus, F. (2026, October). &quot;Multi-Day Horizon Solar Power Forecasting.&quot; <i>In 2026 IEEE 58th North American Power Symposium (NAPS)</i>. IEEE.'
---

Solar photovoltaic (PV) forecasting has evolved from simple regression to complex models such as gradient boosting and transformers. Studies rarely isolate the contribution of pre-processing from that of algorithm selection. We developed a Systematic Pre-Modeling Optimization Framework (SPOF), a three-step framework that includes: (1) filtering zero-production night records, (2) expanding six meteorological inputs into 26 predictors via cyclic time encodings, physics-inspired interactions and temporal lag features, and (3) applying a log transformation. In this paper, pre-processing contributed approximately twice as much accuracy gain as algorithm selection, making it the most significant performance lever among the eight models evaluated across four families. We tested various regressors and found that gradient boosting methods performed well with minimal overfitting, even with only 30% of the training data. The framework was evaluated on two solar datasets from different sources, yielding consistent results. The Histogram-Based Gradient Boosting Regressor (HGBR) demonstrated consistently high predictive accuracy across all forecast horizons from 1 to 15 days, with the Coefficient of Determination ($R^2$) ranging from 0.90 to 0.99, without requiring high-performance computing infrastructure. The key contribution of this paper is prioritizing pre-processing before algorithm comparison.



<!--slidesurl: 'http://academicpages.github.io/files/slides1.pdf'

paperurl: '[https://www.researchgate.net/publication/415517916_Disagreement-Gated_Graph-Residual_Correction_for_Mismatched_MWPM_Decoding_in_Surface_Codes](https://www.researchgate.net/publication/415517916_Disagreement-Gated_Graph-Residual_Correction_for_Mismatched_MWPM_Decoding_in_Surface_Codes)'

paperurl: 'http://academicpages.github.io/files/paper1.pdf'
bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
-->
