---
title: "A Differentially Private Linear-Time fPTAS for the Minimum Enclosing Ball Problem"
collection: publications
category: conferences
permalink: /publication/2022-12-01-dp-fptas-meb
excerpt: "We design the first differentially private linear-time fPTAS for Minimum Enclosing Ball, matching non-private efficiency while providing formal privacy guarantees."
# date: 2022-12-01
venue: "NeurIPS 2022"
slidesurl: '/files/mahpud_sheffet_neurips2022_slides.pdf'
paperurl: '/files/mahpud_sheffet_neurips2022_paper.pdf'
bibtexurl: '/files/mahpud_sheffet_neurips2022.bib'
citation: 'Mahpud, Bar; Sheffet, Or. (2022). &quot;A Differentially Private Linear-Time fPTAS for the Minimum Enclosing Ball Problem.&quot; <i>NeurIPS 2022</i>.'
---
The Minimum Enclosing Ball (MEB) problem is one of the most fundamental problems in clustering, with applications in operations research, statistics and computational geometry. In this works, we give the first differentially private (DP) fPTAS for the Minimum Enclosing Ball problem, improving both on the runtime and the utility bound of the best known DP-PTAS for the problem, of Ghazi et al. (2020). Given n points in \R^d that are covered by the ball B(\theta_{opt},r_{opt}), our simple iterative DP-algorithm returns a ball B(\theta,r) where r\leq (1+\gamma)r_{opt} and which leaves at most \tilde O(\frac{\sqrt d}{\gamma\epsilon}) points uncovered in \tilde O(\nicefrac n {\gamma^2})-time. We also give a local-model version of our algorithm, that leaves at most \tilde O(\frac{\sqrt {nd}}{\gamma\epsilon}) points uncovered, improving on the n^{0.67}-bound of Nissim and Stemmer (2018) (at the expense of other parameters). In addition, we test our algorithm empirically and discuss future open problems.