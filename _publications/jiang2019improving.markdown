---
layout: publication
title: Improving Neural Response Diversity With Frequency45;aware Cross45;entropy Loss
authors: Jiang Shaojie, Ren Pengjie, Monz Christof, De Rijke Maarten
conference: "Arxiv"
year: 2019
bibkey: jiang2019improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1902.09191"}
tags: ['Applications', 'RAG']
---
Sequence45;to45;Sequence (Seq2Seq) models have achieved encouraging performance on the dialogue response generation task. However existing Seq2Seq45;based response generation methods suffer from a low45;diversity problem they frequently generate generic responses which make the conversation less interesting. In this paper we address the low45;diversity problem by investigating its connection with model over45;confidence reflected in predicted distributions. Specifically we first analyze the influence of the commonly used Cross45;Entropy (CE) loss function and find that the CE loss function prefers high45;frequency tokens which results in low45;diversity responses. We then propose a Frequency45;Aware Cross45;Entropy (FACE) loss function that improves over the CE loss function by incorporating a weighting mechanism conditioned on token frequency. Extensive experiments on benchmark datasets show that the FACE loss function is able to substantially improve the diversity of existing state45;of45;the45;art Seq2Seq response generation methods in terms of both automatic and human evaluations.
