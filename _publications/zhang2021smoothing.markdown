---
layout: publication
title: Smoothing Dialogue States for Open Conversational Machine Reading
authors: Zhang Zhuosheng, Ouyang Siru, Zhao Hai, Utiyama Masao, Sumita Eiichiro
conference: "Arxiv"
year: 2021
bibkey: zhang2021smoothing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.12599"}
tags: []
---
Conversational machine reading (CMR) requires machines to communicate with humans through multi-turn interactions between two salient dialogue states of decision making and question generation processes. In open CMR settings as the more realistic scenario the retrieved background knowledge would be noisy which results in severe challenges in the information transmission. Existing studies commonly train independent or pipeline systems for the two subtasks. However those methods are trivial by using hard-label decisions to activate question generation which eventually hinders the model performance. In this work we propose an effective gating strategy by smoothing the two dialogue states in only one decoder and bridge decision making and question generation to provide a richer dialogue state reference. Experiments on the OR-ShARC dataset show the effectiveness of our method which achieves new state-of-the-art results.
