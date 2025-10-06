---
title: "Differentially Private Learning of Exponential Distributions: Adaptive Algorithms and Tight Bounds"
collection: publications
category: conferences
permalink: /publication/2025-11-01-dp-exponential-learning
excerpt: "We develop two complementary pure-DP methods for learning Exponential Distributions—a clipped-noisy MLE and a quantile estimator—combine them adaptively to attain near-optimal sample complexity; extend via a logarithmic reduction to Pareto; prove nearly matching lower bounds (packing & group privacy); and show that approximate-DP removes the need for external bounds."
# date: 2025-11-01
venue: "(under review)"
# slidesurl: '/files/mahpud_sheffet_dp_exponential_slides.pdf'
paperurl: '/files/mahpud_sheffet_dp_exponential_preprint.pdf'
bibtexurl: '/files/mahpud_sheffet_dp_exponential.bib'
citation: 'Mahpud, Bar; Sheffet, Or. (2025). &quot;Differentially Private Learning of Exponential Distributions: Adaptive Algorithms and Tight Bounds.&quot; <i>AISTATS 2026</i> (under review).'
---
We study the problem of learning exponential distributions under differential privacy. Given n i.i.d. samples from \mathrm{Exp}(\lambda), the goal is to privately estimate \lambda so that the learned distribution is close in total variation distance to the truth. We present two complementary pure DP algorithms: one adapts the classical maximum likelihood estimator via clipping and Laplace noise, while the other leverages the fact that the (1-1/e)-quantile equals 1/\lambda. Each method excels in a different regime, and we combine them into an adaptive best-of-both algorithm achieving near-optimal sample complexity for all \lambda. We further extend our approach to Pareto distributions via a logarithmic reduction, prove nearly matching lower bounds using packing and group privacy \cite{Karwa2017FiniteSD}, and show how approximate (\epsilon,\delta)-DP removes the need for externally supplied bounds. Together, these results give the first tight characterization of exponential distribution learning under DP and illustrate the power of adaptive strategies for heavy-tailed laws.