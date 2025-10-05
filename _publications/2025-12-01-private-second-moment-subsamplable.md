---
title: "A Private Approximation of the 2nd-Moment Matrix of Any Subsamplable Input"
collection: publications
category: conferences
permalink: /publication/2025-12-01-private-second-moment-subsamplable
excerpt: "General-purpose algorithms for privately approximating second-moment matrices under subsamplability assumptions, with tight bounds and practical accuracy."
# date: 2025-12-01
venue: "NeurIPS 2025"
slidesurl: '/files/mahpud_sheffet_neurips2025_slides.pdf'
paperurl: '/files/mahpud_sheffet_neurips2025_paper.pdf'
bibtexurl: '/files/mahpud_sheffet_neurips2025.bib'
citation: 'Mahpud, Bar; Sheffet, Or. (2025). &quot;A Private Approximation of the 2nd-Moment Matrix of Any Subsamplable Input.&quot; <i>NeurIPS 2025</i>.'
---
We study the problem of differentially private second moment estimation and present a new algorithm that achieve strong privacy-utility trade-offs even for worst-case inputs under subsamplability assumptions on the data. We call an input (m,\alpha,\beta)-subsamplable if a random subsample of size m (or larger) preserves w.p \geq 1-\beta the spectral structure of the original second moment matrix up to a multiplicative factor of 1\pm \alpha. Building upon subsamplability, we give a recursive algorithmic framework similar to Kamath et al 2019, that abides zero-Concentrated Differential Privacy (zCDP) while preserving w.h.p. the accuracy of the second moment estimation upto an arbitrary factor of (1\pm\gamma). We then show how to apply our algorithm to approximate the second moment matrix of a distribution \mathcal{D}, even when a noticeable fraction of the input are outliers.