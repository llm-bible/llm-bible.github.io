---
layout: publication
title: 'An Engorgio Prompt Makes Large Language Model Babble On'
authors: Jianshuo Dong, Ziyuan Zhang, Qingjie Zhang, Tianwei Zhang, Hao Wang, Hewu Li, Qi Li, Chao Zhang, Ke Xu, Han Qiu
conference: "Arxiv"
year: 2024
bibkey: dong2024engorgio
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.19394'}
  - {name: "Code", url: 'https://github.com/jianshuod/Engorgio-prompt'}
tags: ['Reinforcement Learning', 'Prompting', 'Has Code', 'Security']
---
Auto-regressive large language models (LLMs) have yielded impressive
performance in many real-world tasks. However, the new paradigm of these LLMs
also exposes novel threats. In this paper, we explore their vulnerability to
inference cost attacks, where a malicious user crafts Engorgio prompts to
intentionally increase the computation cost and latency of the inference
process. We design Engorgio, a novel methodology, to efficiently generate
adversarial Engorgio prompts to affect the target LLM's service availability.
Engorgio has the following two technical contributions. (1) We employ a
parameterized distribution to track LLMs' prediction trajectory. (2) Targeting
the auto-regressive nature of LLMs' inference process, we propose novel loss
functions to stably suppress the appearance of the <EOS> token, whose
occurrence will interrupt the LLM's generation process. We conduct extensive
experiments on 13 open-sourced LLMs with parameters ranging from 125M to 30B.
The results show that Engorgio prompts can successfully induce LLMs to generate
abnormally long outputs (i.e., roughly 2-13\\(\times\\) longer to reach 90%+ of the
output length limit) in a white-box scenario and our real-world experiment
demonstrates Engergio's threat to LLM service with limited computing resources.
The code is released at: https://github.com/jianshuod/Engorgio-prompt.
