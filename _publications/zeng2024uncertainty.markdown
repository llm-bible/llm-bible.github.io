---
layout: publication
title: 'Uncertainty Is Fragile: Manipulating Uncertainty In Large Language Models'
authors: Qingcheng Zeng, Mingyu Jin, Qinkai Yu, Zhenting Wang, Wenyue Hua, Zihao Zhou, Guangyan Sun, Yanda Meng, Shiqing Ma, Qifan Wang, Felix Juefei-xu, Kaize Ding, Fan Yang, Ruixiang Tang, Yongfeng Zhang
conference: "Arxiv"
year: 2024
bibkey: zeng2024uncertainty
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.11282'}
  - {name: "Code", url: 'https://github.com/qcznlp/uncertainty_attack'}
tags: ['RAG', 'Has Code', 'Prompting', 'Security']
---
Large Language Models (LLMs) are employed across various high-stakes domains,
where the reliability of their outputs is crucial. One commonly used method to
assess the reliability of LLMs' responses is uncertainty estimation, which
gauges the likelihood of their answers being correct. While many studies focus
on improving the accuracy of uncertainty estimations for LLMs, our research
investigates the fragility of uncertainty estimation and explores potential
attacks. We demonstrate that an attacker can embed a backdoor in LLMs, which,
when activated by a specific trigger in the input, manipulates the model's
uncertainty without affecting the final output. Specifically, the proposed
backdoor attack method can alter an LLM's output probability distribution,
causing the probability distribution to converge towards an attacker-predefined
distribution while ensuring that the top-1 prediction remains unchanged. Our
experimental results demonstrate that this attack effectively undermines the
model's self-evaluation reliability in multiple-choice questions. For instance,
we achieved a 100 attack success rate (ASR) across three different triggering
strategies in four models. Further, we investigate whether this manipulation
generalizes across different prompts and domains. This work highlights a
significant threat to the reliability of LLMs and underscores the need for
future defenses against such attacks. The code is available at
https://github.com/qcznlp/uncertainty_attack.
