---
title: "Fast Beam Training for Wideband ELAA Systems with Uniform Circular Array"
collection: talks
type: "Talk"
permalink: /research/UCA
venue: "UC-Berkeley Institute for Testing Science"
date: 2018-03-01
location: "Berkeley CA, USA"
---

<font size = 4><b>Analyze the frequency-dependent focusing property in wideband uniform circular array (UCA) systems. Propose an effective beam training framework to estimate the angle and distance simultaneously.</b></font>

<p></p>

Extremely large-scale antenna array (ELAA) at millimeter wave (mmWave) and terahertz (THz) band has been considered as a key technology for future 6G communications to combat the high attenuation in high-frequency bands. With the capability of providing flat beamforming gain in all angles, uniform circular array (UCA) has attracted a lot of attention. To realize efficient beamforming, beam training is widely utilized to acquire the channel state information (CSI). However, with a large antenna number, the beam training overhead in ELAA systems becomes overwhelming. Moreover, with a large bandwidth, the beam defocus effect causes a severe degradation in the beam training accuracy. 

![defocus](https://hericenes.github.io/yuhaochen.github.io/images/UCA-1.png)

To deal with these problems, we propose a frequency-dependent focusing (FDF) based beam training scheme to realize effective beam training in near-field wideband ELAA systems with UCA. Specifically, we first analyze the FDF property of UCA, where signals at different subcarriers can focus on different distances at the same time. 

![FDF](https://hericenes.github.io/yuhaochen.github.io/images/UCA-2.png)

Then, by exploiting the FDF property to search different distances by different subcarriers simultaneously, we design the hierarchical codebook and propose a FDF based beam training scheme. 

![codebook](https://hericenes.github.io/yuhaochen.github.io/images/UCA-3.png)

Moreover, we compare the necessary beam training overhead of the proposed scheme with those of existing schemes to reveal the effectiveness of the proposed scheme. Simulation results illustrate that the proposed scheme can realize an accurate beam training in near-field wideband UCA systems with a low beam training overhead.
