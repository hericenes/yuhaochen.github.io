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

![overview](../images/mmWave-prototype.png)

## AI-based end-to-end architecture

We break the traditional paradigm which divide the communication system into several modules. In order to realize a better performance, we train an end-to-end system off-line and deploy it on the FPGA.

![end-to-end](../images/end-to-end.png)

The end-to-end system demonstrates several interesting results, including the unconventional constellation diagrams. The constellation diagrams vary with different training targets (e.g., minimum BER, mininum SER, etc.). This phenomenon reveals the potential of enhancing the performance of communication systems with AI.

## Algorithm verification

We also utilize this prototype to verify the performance of the proposed [analytical beam training framework](https://hericenes.github.io/yuhaochen.github.io/research/analytical) and the proposed [FDF-based beam training framework](https://hericenes.github.io/yuhaochen.github.io/research/UCA).