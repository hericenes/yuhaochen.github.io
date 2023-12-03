---
title: "RIS-Assisted Communication Prototype @ 28 GHz"
collection: teaching
type: "Undergraduate course"
permalink: /demos/mmWave
venue: "University 1, Department"
date: 2015-01-01
location: "City, Country"
---

<font size = 4><b>This prototype integrates a 2304-element RIS and an AI-based end-to-end architecture.</b></font>

<p></p>

![overview](https://hericenes.github.io/yuhaochen.github.io/images/mmWave-prototype.png)

## AI-based end-to-end architecture

We break the traditional paradigm which divide the communication system into several modules. In order to realize a better performance, we train an end-to-end system off-line and deploy it on the FPGA.

![end-to-end](https://hericenes.github.io/yuhaochen.github.io/images/end-to-end.png)

The end-to-end system demonstrates several interesting results, including the unconventional constellation diagrams. The constellation diagrams vary with different training targets (e.g., minimum BER, mininum SER, etc.). This phenomenon reveals the potential of enhancing the performance of communication systems with AI.

![constellation](https://hericenes.github.io/yuhaochen.github.io/images/constellation.png)

## Algorithm verification & Field test

We utilize this prototype to verify the performance of the proposed [analytical beam training framework](https://hericenes.github.io/yuhaochen.github.io/research/analytical) and the proposed [FDF-based beam training framework](https://hericenes.github.io/yuhaochen.github.io/research/UCA). In addition, we verify the performance of the proposed [dynamic codebook](https://hericenes.github.io/yuhaochen.github.io/research/Accurate).

![codebook result](https://hericenes.github.io/yuhaochen.github.io/images/codebook-test.png)

We also conduct field test based on the prototype. The results were reported at Global 6G Development Conference, 2022. 

![result](https://hericenes.github.io/yuhaochen.github.io/images/mmWave-result.png)