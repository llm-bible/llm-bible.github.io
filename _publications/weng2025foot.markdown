---
layout: publication
title: 'Foot-in-the-door: A Multi-turn Jailbreak For Llms'
authors: Zixuan Weng, Xiaolong Jin, Jinyuan Jia, Xiangyu Zhang
conference: "Arxiv"
year: 2025
bibkey: weng2025foot
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.19820'}
  - {name: "Code", url: 'https://github.com/Jinxiaolong1129/Foot-in-the-door-Jailbreak'}
tags: ['Has Code', 'RAG', 'Security', 'Applications', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
Ensuring AI safety is crucial as large language models become increasingly
integrated into real-world applications. A key challenge is jailbreak, where
adversarial prompts bypass built-in safeguards to elicit harmful disallowed
outputs. Inspired by psychological foot-in-the-door principles, we introduce
FITD,a novel multi-turn jailbreak method that leverages the phenomenon where
minor initial commitments lower resistance to more significant or more
unethical transgressions. Our approach progressively escalates the malicious
intent of user queries through intermediate bridge prompts and aligns the
model's response by itself to induce toxic responses. Extensive experimental
results on two jailbreak benchmarks demonstrate that FITD achieves an average
attack success rate of 94% across seven widely used models, outperforming
existing state-of-the-art methods. Additionally, we provide an in-depth
analysis of LLM self-corruption, highlighting vulnerabilities in current
alignment strategies and emphasizing the risks inherent in multi-turn
interactions. The code is available at
https://github.com/Jinxiaolong1129/Foot-in-the-door-Jailbreak.
