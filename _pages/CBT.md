---
title: "Coded Beam Training for RIS-Assisted Communication Systems"
collection: talks
type: "Talk"
permalink: /research/RIS/CBT-RIS
venue: "UC-Berkeley Institute for Testing Science"
date: 2019-03-01
location: "Berkeley CA, USA"
---

<font size = 4><b>Design a beam training framework in RIS systems based on the idea of channel coding to enhance the beam training accuracy. Propose a novel codeword design scheme and an encoder design scheme based on the hardware constraints of RIS.</b></font>

<p></p>

In RIS-assisted communication systems for future sixth-generation (6G) communications, codebook-based beam training stands out as a promising technology to acquire channel state information (CSI). Despite their effectiveness, when the pilot overhead is limited, existing beam training methods suffer from significant achievable rate degradation for remote users with low signal-to-noise ratio (SNR). Due to the "multiplicative fading" effect in RIS systems, the beam training accuracy is severely limited.

![fading](https://hericenes.github.io/yuhaochen.github.io/images/CBT-1.png)

To tackle this challenge, leverging the error-correcting capability of channel codes, we introduce channel coding theory into hierarchical beam training to extend the coverage area. Specifically, we first establish the duality between hierarchical beam training and channel coding. 

![framework](https://hericenes.github.io/yuhaochen.github.io/images/CBT-2.png)

In order to realize effective codeword design in RIS systems, we then propose a new codeword design criterion, based on which we propose a relaxed Gerchberg-Saxton (GS) based codeword design scheme by considering the constant modulus constraints of RIS elements. In addition, considering the two dimensional structure of RIS, we further propose a dimension reduced encoder design scheme, which can not only guarentee a better beam shape, but also enable a stronger error correction capability. Simulation results reveal that the proposed scheme can realize effective and accurate beam training in low SNR scenarios.

![GS](https://hericenes.github.io/yuhaochen.github.io/images/GS-scheme.png)

-----

1. **Y. Chen** and L. Dai, “Coded beam training for RIS assisted wireless communications,” submitted to *IEEE Transactions on Wireless Communications*. [(arXiv)](https://hericenes.github.io/yuhaochen.github.io/files/Coded_beam_training_for_RIS_assisted_wireless_communications.pdf)

----

### [Next: Accurate & Effective Channel Estimation for Extremely Large-Scale RIS](https://hericenes.github.io/yuhaochen.github.io/research/RIS/Accurate)

## [<<BACK](https://hericenes.github.io/yuhaochen.github.io/research/RIS)
