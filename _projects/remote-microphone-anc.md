---
layout: page
title: Remote Microphone Technique for ANC
description: Distributed remote-microphone active noise control to create zones of quiet without intrusive error sensors.
img: # add assets/img/xxx.png if you want an image
importance: 2
category: work
---

Flagship research published in the **IEEE/ACM Transactions on Audio, Speech, and Language Processing** (2023), where I was first author.

We introduced the **Remote Microphone (RM) technique** into distributed active noise control systems. This makes it possible to project a zone of quiet at a target position — for example near the ears of passengers in a car, plane or public transport — **without placing error microphones at the listener**, which would be intrusive.

The proposed algorithm, a distributed variant of the filtered-x LMS named **RM-DMEFxLMS**, achieves performance comparable to centralized systems while reducing computational demands on a single processor and offering scalability and versatility for practical ANC applications.

- DOI: [10.1109/TASLP.2023.3264600](https://doi.org/10.1109/TASLP.2023.3264600)
- Open code & measurements: [GitHub](https://github.com/chrisantman/RM-technique-for-ANC-over-distributed-networks)
- Repository (ReUnir): [UNIR institutional repository](https://reunir.unir.net/handle/123456789/15411)