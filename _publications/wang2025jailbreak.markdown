---
layout: publication
title: 'JULI: Jailbreak Large Language Models By Self-introspection'
authors: Jesson Wang, Zhanhao Hu, David Wagner
conference: "Arxiv"
year: 2025
bibkey: wang2025jailbreak
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.11790'}
tags: ['Ethics and Bias', 'Security', 'Responsible AI', 'Tools']
---
Large Language Models (LLMs) are trained with safety alignment to prevent generating malicious content. Although some attacks have highlighted vulnerabilities in these safety-aligned LLMs, they typically have limitations, such as necessitating access to the model weights or the generation process. Since proprietary models through API-calling do not grant users such permissions, these attacks find it challenging to compromise them. In this paper, we propose Jailbreaking Using LLM Introspection (JULI), which jailbreaks LLMs by manipulating the token log probabilities, using a tiny plug-in block, BiasNet. JULI relies solely on the knowledge of the target LLM's predicted token log probabilities. It can effectively jailbreak API-calling LLMs under a black-box setting and knowing only top-\\(5\\) token log probabilities. Our approach demonstrates superior effectiveness, outperforming existing state-of-the-art (SOTA) approaches across multiple metrics.
