---
title: "Evaluating Energy Efficiency of AI Accelerators Using Two MLPerf Benchmarks"
collection: publications
category: conferences
permalink: /publication/2025-05-22-mlperfPower
excerpt: 'This paper conducts an initial study to evaluate the energy requirements of four AI accelerators: Nvidia A100 GPUs, Intel Habana Gaudi Processing Units (HPUs), Graphcore Bow-Pod64 Intelligence Processing Units (IPUs), and GroqRack Language Processing Units (LPUs) using two popular MLPerf benchmarks: BERT-Large and ResNet50.'
date: 2025-05-22
venue: 'IEEE International Symposium on Cluster, Cloud, and Internet Computing (CCGrid)'
citation: 'Ferdaus, F., Wu, X., Taylor, V., Lan, Z., Shanmugavelu, S., Vishwanath, V., & Papka, M. E. (2025, May). &quot;Evaluating Energy Efficiency of Ai Accelerators Using Two Mlperf Benchmarks.&quot; <i>In 2025 IEEE 25th International Symposium on Cluster, Cloud and Internet Computing (CCGrid)</i>. (pp. 549-558). IEEE.'
---

The significantly increasing use of artificial intelligence (AI) has led to the availability of specialized AI accelerators, aiming to enhance the performance and energy efficiency of AI workloads. In this paper, we conduct an initial study to evaluate the energy requirements of four AI accelerators: Nvidia A100 GPUs, Intel Habana Gaudi Processing Units (HPUs), Graphcore Bow-Pod64 Intelligence Processing Units (IPUs), and GroqRack Language Processing Units (LPUs) using two popular MLPerf benchmarks: BERT-Large and ResNet50. We report the energy requirements for the two benchmarks to achieve a common MLPerfspecified target accuracy. The benchmarks and AI accelerators were chosen based on the following criteria: publicly available tools or libraries from the vendors to monitor power consumption, publicly available optimized models from the vendors, and access to the AI accelerators. Our experimental results indicate that for ResNet50, Intel Gaudi2 HPUs delivered the highest throughput, the lowest energy consumption for both training and inference, and the highest inference energy efficiency, while Graphcore demonstrated the highest training energy efficiency. For BERTLarge pre-training, Intel Gaudi2 outperformed both Nvidia A100 and Graphcore in terms of time, energy consumption, and training energy efficiency. However, for BERT-Large inference, Nvidia A100 achieved the shortest time and lowest energy consumption; Graphcore exhibited the highest throughput in both pre-training and inference, along with the highest inference energy efficiency. We discuss our observations and findings while exploring the associated tradeoffs.

<!--slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.-->
