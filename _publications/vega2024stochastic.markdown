---
layout: publication
title: 'Stochastic Monkeys At Play: Random Augmentations Cheaply Break LLM Safety Alignment'
authors: Jason Vega, Junsheng Huang, Gaokai Zhang, Hangoo Kang, Minjia Zhang, Gagandeep Singh
conference: "Arxiv"
year: 2024
bibkey: vega2024stochastic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.02785'}
  - {name: "Code", url: 'https://github.com/uiuc-focal-lab/stochastic-monkeys/'}
tags: ['Has Code', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Quantization', 'Fine-Tuning', 'Prompting', 'Responsible AI', 'Pretraining Methods']
---
Safety alignment of Large Language Models (LLMs) has recently become a
critical objective of model developers. In response, a growing body of work has
been investigating how safety alignment can be bypassed through various
jailbreaking methods, such as adversarial attacks. However, these jailbreak
methods can be rather costly or involve a non-trivial amount of creativity and
effort, introducing the assumption that malicious users are high-resource or
sophisticated. In this paper, we study how simple random augmentations to the
input prompt affect safety alignment effectiveness in state-of-the-art LLMs,
such as Llama 3 and Qwen 2. We perform an in-depth evaluation of 17 different
models and investigate the intersection of safety under random augmentations
with multiple dimensions: augmentation type, model size, quantization,
fine-tuning-based defenses, and decoding strategies (e.g., sampling
temperature). We show that low-resource and unsophisticated attackers, i.e.
\\(\textit\{stochastic monkeys\}\\), can significantly improve their chances of
bypassing alignment with just 25 random augmentations per prompt. Source code
and data: https://github.com/uiuc-focal-lab/stochastic-monkeys/
