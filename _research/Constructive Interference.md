---
title: "Constructive Interference"
layout: single-portfolio
excerpt: "<img src='/images/research/map.png' alt=''>"
collection: research
order_number: 20
header: 
  og_image: "research/map.png"
---

Backscatter communication (BackCom), one of the core technologies to realize zero-power communication, is expected to be a pivotal paradigm for the next generation of the Internet of Things (IoT). However, the “strong” direct link (DL) interference (DLI) is traditionally assumed to be harmful, and generally drowns out the “weak” backscattered signals accordingly, thus deteriorating the performance of BackCom. In contrast to the previous efforts to eliminate the DLI, in this paper, we exploit the constructive interference (CI), in which the DLI contributes to the backscattered signal. To be specific, our objective is to maximize the received signal-to-noise ratio (SNR) by jointly optimizing the receive beamforming vectors and tag selection factors under different detection error probability (DEP) requirements, which leads to two different optimization problems. However, the resulting problems are non-convex and unanalyzable due to constraints on the DEP. To solve these problems, the Kullback-Leibler divergence is first applied to transform the DEP into a tractable form. Then, inspired by the alternating optimization, we respectively propose two successive convex approximation (SCA)-based algorithms to solve the corresponding sub-problems with beamforming design, and a greedy algorithm to solve the sub-problem with tag selection. In order to gain insight into the CI, we consider a special case with the single-antenna reader to reveal the channel angle between the backscattering link (BL) and the DL, in which the DLI will become constructive. Simulation results show that significant performance gain can always be achieved with the proposed algorithms compared to the traditional algorithms without the CI in terms of the received SNR. The derived constructive channel angle for the BackCom system with a single-antenna reader is also confirmed by simulation results.

## Article

CB. Gu, D. Li, Y. Liu and Y. Xu, "Exploiting Constructive Interference for Backscatter Communication Systems," in IEEE Transactions on Communications, vol. 71, no. 7, pp. 4344-4359, July 2023, doi: 10.1109/TCOMM.2023.3277519.


