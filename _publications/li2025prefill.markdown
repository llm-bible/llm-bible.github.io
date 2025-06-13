---
layout: publication
title: 'Prefill-based Jailbreak: A Novel Approach Of Bypassing LLM Safety Boundary'
authors: Yakai Li, Jiekang Hu, Weiduan Sang, Luping Ma, Jing Xie, Weijuan Zhang, Aimin Yu, Shijie Zhao, Qingjia Huang, Qihang Zhou
conference: "Arxiv"
year: 2025
bibkey: li2025prefill
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.21038'}
tags: ['RAG', 'Responsible AI', 'Security', 'Prompting']
---
Large Language Models (LLMs) are designed to generate helpful and safe
content. However, adversarial attacks, commonly referred to as jailbreak, can
bypass their safety protocols, prompting LLMs to generate harmful content or
reveal sensitive data. Consequently, investigating jailbreak methodologies is
crucial for exposing systemic vulnerabilities within LLMs, ultimately guiding
the continuous implementation of security enhancements by developers. In this
paper, we introduce a novel jailbreak attack method that leverages the
prefilling feature of LLMs, a feature designed to enhance model output
constraints. Unlike traditional jailbreak methods, the proposed attack
circumvents LLMs' safety mechanisms by directly manipulating the probability
distribution of subsequent tokens, thereby exerting control over the model's
output. We propose two attack variants: Static Prefilling (SP), which employs a
universal prefill text, and Optimized Prefilling (OP), which iteratively
optimizes the prefill text to maximize the attack success rate. Experiments on
six state-of-the-art LLMs using the AdvBench benchmark validate the
effectiveness of our method and demonstrate its capability to substantially
enhance attack success rates when combined with existing jailbreak approaches.
The OP method achieved attack success rates of up to 99.82% on certain models,
significantly outperforming baseline methods. This work introduces a new
jailbreak attack method in LLMs, emphasizing the need for robust content
validation mechanisms to mitigate the adversarial exploitation of prefilling
features. All code and data used in this paper are publicly available.
