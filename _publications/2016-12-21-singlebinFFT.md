---
#title: "Paper Title Number 5, with math $$E=mc^2$$"
title: "Use of single bin Fourier transform algorithm for high speed tone detection and parallel processing"
collection: publications
category: conferences
permalink: /publication/2016-12-21-singlebinFFT
#excerpt: 'This paper is about a famous math equation, $$E=mc^2$$'
excerpt: 'This paper introduces the single bin Fourier transform algorithm, which efficiently computes the spectral amplitude and phase of a specific frequency in a signal. It is used for tone detection, offering a simpler and more computationally efficient alternative to the traditional FFT. The approach also supports parallel processing to detect multiple frequencies simultaneously. The primary goal is to enhance the speed of detecting single or narrow-band frequencies in a signal.'
date: 2016-12-21
venue: 'International Conference on Electrical and Computer Engineering (ICECE)'
#paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
citation: 'Sakib, S. K., Ferdaus, F., & Rahman, M. S. (2016). &quot;Use of single bin Fourier transform algorithm for high speed tone detection and parallel processing.&quot; <i>In 2016 9th International Conference on Electrical and Computer Engineering (ICECE)</i>. (pp. 214-217). IEEE.'
---

Fourier transform is the classical tool for performing spectral analysis of a short-duration signal and fast Fourier transform (FFT) is the widely used algorithm for achieving the same with a high degree of computational efficiency. Recently a “single bin Fourier transform algorithm” has been proposed by the present authors, which is designed to compute the spectral amplitude and phase of a single frequency present in the time signal to be analyzed. The traditional detection scheme involves sampling the analog signal first using the Nyquist's sampling theorem, apply the FFT on the sampled signal and then identify the desired frequency from the FFT output. However, in case of tone detection, only the presence of a single frequency is to be tested. The computation of the whole FFT output dataset is superfluous in this case. In this paper, we have used the single bin Fourier transform algorithm for tone detection, which makes the detection scheme less complex and computationally more efficient than the traditional FFT algorithm. Moreover, the method of parallel processing can be applied to make the system more efficient in detecting the existence of more than one frequency component present in the incoming signal. The main objective of the proposed scheme is to improve the detection speed of a single frequency, or a narrow band of frequencies, present in a signal.
<!--Using [MathJax](https://www.mathjax.org/) in the description is supported - $$E=mc^2$$ - however, the use must be mindful that the default delimiters are `$$...$$` and `\\[...\\]` which differs from the `$...$` that is typically expected.-->
