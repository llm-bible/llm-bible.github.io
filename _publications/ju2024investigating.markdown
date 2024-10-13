---
layout: publication
title: 'Investigating Multi-hop Factual Shortcuts In Knowledge Editing Of Large Language Models'
authors: Ju Tianjie, Chen Yijin, Yuan Xinwei, Zhang Zhuosheng, Du Wei, Zheng Yubin, Liu Gongshen
conference: "Arxiv"
year: 2024
bibkey: ju2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11900"}
tags: ['Few Shot', 'In Context Learning', 'Prompting', 'RAG', 'Training Techniques']
---
Recent work has showcased the powerful capability of large language models
(LLMs) in recalling knowledge and reasoning. However, the reliability of LLMs
in combining these two capabilities into reasoning through multi-hop facts has
not been widely explored. This paper systematically investigates the
possibilities for LLMs to utilize shortcuts based on direct connections between
the initial and terminal entities of multi-hop knowledge. We first explore the
existence of factual shortcuts through Knowledge Neurons, revealing that: (i)
the strength of factual shortcuts is highly correlated with the frequency of
co-occurrence of initial and terminal entities in the pre-training corpora;
(ii) few-shot prompting leverage more shortcuts in answering multi-hop
questions compared to chain-of-thought prompting. Then, we analyze the risks
posed by factual shortcuts from the perspective of multi-hop knowledge editing.
Analysis shows that approximately 20% of the failures are attributed to
shortcuts, and the initial and terminal entities in these failure instances
usually have higher co-occurrences in the pre-training corpus. Finally, we
propose erasing shortcut neurons to mitigate the associated risks and find that
this approach significantly reduces failures in multiple-hop knowledge editing
caused by shortcuts.
