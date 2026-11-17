---
title: "Horizon-Adaptive Residual Learning for Multi-Horizon Phycocyanin Forecasting"
collection: publications
category: conferences
permalink: /publication/2027-02-14-SSCI-water
excerpt: 'This paper proposes a residual estimation framework for multi-horizon phycocyanin forecasting, introducing the Horizon Conditioned Residual (HCR)-LightGBM and Horizon Adaptive Residual Persistence (HARP) Ensemble to improve long-range cyanobacterial bloom prediction across multiple forecast horizons.'
date: 2027-02-14
venue: '2027 IEEE Symposium Series on Computational Intelligence (SSCI)'
---

Phycocyanin fluorescence serves as a continuous indicator of cyanobacterial biomass, with multi-horizon forecasting aiding early bloom detection and water treatment planning. Long-term prediction presents challenges due to diminishing dependence between current and future states as lead time increases. This study redefines multi-horizon phycocyanin forecasting as a residual estimation problem: each model predicts the deviation of the future value from the most recent observation, inherently maintaining persistence. We evaluate direct and residual variants of Random Forest, XGBoost, and LightGBM models; introduce the Horizon Conditioned Residual (HCR)-LightGBM, which shares residual structure across different lead times by incorporating lead time as an input; and propose the Horizon Adaptive Residual Persistence (HARP) Ensemble, combining persistence, seasonal climatology, and HCR-LightGBM using non-negative weights optimized on validation data. Experiments utilize 15-minute interval records from two USGS stations near Houston, Texas, at six forecast horizons ranging from 12 hours to 10 days. Relative to the best-performing direct models, residual and hybrid methods decrease the mean root-mean-square error (RMSE) by 19.57% at Station A and 27.03% at Station B. Additionally, they maintain positive $R^2$ values at longer horizons where direct models often exhibit negative values. The best forecasting method remains station- and horizon-dependent.


<!--slidesurl: 'http://academicpages.github.io/files/slides1.pdf'

paperurl: '[https://www.researchgate.net/publication/415517916_Disagreement-Gated_Graph-Residual_Correction_for_Mismatched_MWPM_Decoding_in_Surface_Codes](https://www.researchgate.net/publication/415517916_Disagreement-Gated_Graph-Residual_Correction_for_Mismatched_MWPM_Decoding_in_Surface_Codes)'

paperurl: 'http://academicpages.github.io/files/paper1.pdf'
bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
citation: 'Chowdhury, M. R., Imam, T., Mamun, M. A., Sifat, A. I. & Ferdaus, F. (2026, October). &quot;Multi-Day Horizon Solar Power Forecasting.&quot; <i>In 2026 IEEE 58th North American Power Symposium (NAPS)</i>. IEEE.'

---
-->
