---
title: "Disagreement-Gated Graph-Residual Correction for Mismatched MWPM Decoding in Surface Codes"
collection: publications
category: conferences
permalink: /publication/2026-09-15-qec
excerpt: 'This paper proposes a decoder-disagreement-gated graph-residual correction framework that improves minimum-weight perfect matching (MWPM) decoding of surface codes under correlated circuit-level noise mismatch. It keeps MWPM as the primary decoder and applies selective residual correction, cutting the logical error rate by an average of 14.57%, 29.56% and 35.63% at code distances 3, 5 and 7.'
date: 2026-09-15
venue: 'Workshop on Advancing Hybrid Quantum-Classical Computing Through Shared Challenges, IEEE International Conference on Quantum Computing and Engineering (QCE)'
---

Minimum-weight perfect matching (MWPM) is one of the most widely used decoders for surface-code quantum error correction. However, its performance deteriorates when the assumed detector error model is mismatched with correlated circuit-level noise. In this work, we propose a decoder-disagreement-gated graph-residual correction framework that enhances mismatched MWPM without replacing it. The proposed hybrid decoder preserves MWPM as the primary decoder and applies selective residual correction using detector syndromes, graph-structured detector features, and decoder-context information only when residual correction is expected to be beneficial. We use direct residual correction as a diagnostic baseline for d = 3 and d = 5, and evaluate the proposed disagreement-gated strategy across d = 3, 5, and 7 under structured correlated-noise mismatch. Results indicate that direct residual correction achieves the strongest improvement at d = 3, with an average logical error rate (LER) reduction of 48.64%. Its effectiveness diminishes at d = 5, with an average reduction of 12.76% over the retained test points. In contrast, the disagreement-gated method maintains positive gains at d = 3, with an average LER reduction of 14.57%, and demonstrates better scalability, achieving average reductions of 29.56% at d = 5 and 35.63% at d = 7. Additionally, the proposed approach consistently improves decoding performance across all evaluated gated configurations, reduces the performance gap relative to the true-DEM PyMatching reference, and maintains positive net correction by correcting more MWPM errors than it introduces. These results show that selective graph-residual correction can improve MWPM surface-code decoding under correlated detector-model mismatch while retaining MWPM as the primary decoder.

paperurl: 'https://www.researchgate.net/publication/415517916_Disagreement-Gated_Graph-Residual_Correction_for_Mismatched_MWPM_Decoding_in_Surface_Codes'

<!--slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
citation: 'Ferdaus, F., Wu, X., Taylor, V., Lan, Z., Shanmugavelu, S., Vishwanath, V., & Papka, M. E. (2025, May). &quot;Evaluating Energy Efficiency of Ai Accelerators Using Two Mlperf Benchmarks.&quot; <i>In 2025 IEEE 25th International Symposium on Cluster, Cloud and Internet Computing (CCGrid)</i>. (pp. 549-558). IEEE.'-->
