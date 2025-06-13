---
layout: publication
title: 'Toward Secure Tuning: Mitigating Security Risks From Instruction Fine-tuning'
authors: Yanrui Du, Sendong Zhao, Jiawei Cao, Ming Ma, Danyang Zhao, Shuren Qi, Fenglei Fan, Ting Liu, Bing Qin
conference: "Arxiv"
year: 2024
bibkey: du2024toward
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.04524'}
tags: ['Security', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Instruction fine-tuning has emerged as a critical technique for customizing
Large Language Models (LLMs) to specific applications. However, recent studies
have highlighted significant security vulnerabilities in fine-tuned LLMs.
Existing defense efforts focus more on pre-training and post-training methods,
yet there remains underexplored in in-training methods. To fill this gap, we
introduce a novel secure-tuning strategy called SWAT. By analyzing how
module-level parameters (e.g. Q/K/V/O) affect the security feature space drift,
we identify a robust subset of modules, termed Mods_Rob. Our SWAT strategy
begins by warming up Mods_Rob to capture low-level features with minimal
security risks, followed by training all parameters to achieve optimal task
performance. Essentially, this strategy shifts the early learning burden more
from global parameters to Mods_Rob, reducing update magnitudes of the
non-robust subset. Across various datasets, scenarios, and LLMs, our strategy
has demonstrated significant success in mitigating security risks while
preserving task performance. Importantly, it can be seamlessly integrated with
pre-training and post-training methods, leading to greater improvements.
