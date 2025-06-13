---
layout: publication
title: 'Rewarding Curse: Analyze And Mitigate Reward Modeling Issues For LLM Reasoning'
authors: Jiachun Li, Pengfei Cao, Yubo Chen, Jiexin Xu, Huaijun Li, Xiaojian Jiang, Kang Liu, Jun Zhao
conference: "Arxiv"
year: 2025
bibkey: li2025rewarding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05188"}
tags: ['Prompting', 'Reinforcement Learning']
---
Chain-of-thought (CoT) prompting demonstrates varying performance under
different reasoning tasks. Previous work attempts to evaluate it but falls
short in providing an in-depth analysis of patterns that influence the CoT. In
this paper, we study the CoT performance from the perspective of effectiveness
and faithfulness. For the former, we identify key factors that influence CoT
effectiveness on performance improvement, including problem difficulty,
information gain, and information flow. For the latter, we interpret the
unfaithful CoT issue by conducting a joint analysis of the information
interaction among the question, CoT, and answer. The result demonstrates that,
when the LLM predicts answers, it can recall correct information missing in the
CoT from the question, leading to the problem. Finally, we propose a novel
algorithm to mitigate this issue, in which we recall extra information from the
question to enhance the CoT generation and evaluate CoTs based on their
information gain. Extensive experiments demonstrate that our approach enhances
both the faithfulness and effectiveness of CoT.
