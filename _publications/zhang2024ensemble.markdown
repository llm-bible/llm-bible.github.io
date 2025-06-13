---
layout: publication
title: 'Enja: Ensemble Jailbreak On Large Language Models'
authors: Jiahao Zhang, Zilong Wang, Ruofan Wang, Xingjun Ma, Yu-gang Jiang
conference: "Arxiv"
year: 2024
bibkey: zhang2024ensemble
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.03603'}
tags: ['Attention Mechanism', 'RAG', 'Security', 'Applications', 'Model Architecture', 'Prompting', 'Responsible AI']
---
As Large Language Models (LLMs) are increasingly being deployed in
safety-critical applications, their vulnerability to potential jailbreaks --
malicious prompts that can disable the safety mechanism of LLMs -- has
attracted growing research attention. While alignment methods have been
proposed to protect LLMs from jailbreaks, many have found that aligned LLMs can
still be jailbroken by carefully crafted malicious prompts, producing content
that violates policy regulations. Existing jailbreak attacks on LLMs can be
categorized into prompt-level methods which make up stories/logic to circumvent
safety alignment and token-level attack methods which leverage gradient methods
to find adversarial tokens. In this work, we introduce the concept of Ensemble
Jailbreak and explore methods that can integrate prompt-level and token-level
jailbreak into a more powerful hybrid jailbreak attack. Specifically, we
propose a novel EnJa attack to hide harmful instructions using prompt-level
jailbreak, boost the attack success rate using a gradient-based attack, and
connect the two types of jailbreak attacks via a template-based connector. We
evaluate the effectiveness of EnJa on several aligned models and show that it
achieves a state-of-the-art attack success rate with fewer queries and is much
stronger than any individual jailbreak.
