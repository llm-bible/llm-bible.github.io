---
layout: publication
title: Multi-turn Context Jailbreak Attack On Large Language Models From First Principles
authors: Sun Xiongtao, Zhang Deyue, Yang Dongdong, Zou Quanchen, Li Hui
conference: "Arxiv"
year: 2024
bibkey: sun2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04686"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Reinforcement Learning', 'Security']
---
Large language models (LLMs) have significantly enhanced the performance of numerous applications from intelligent conversations to text generation. However their inherent security vulnerabilities have become an increasingly significant challenge especially with respect to jailbreak attacks. Attackers can circumvent the security mechanisms of these LLMs breaching security constraints and causing harmful outputs. Focusing on multi-turn semantic jailbreak attacks we observe that existing methods lack specific considerations for the role of multiturn dialogues in attack strategies leading to semantic deviations during continuous interactions. Therefore in this paper we establish a theoretical foundation for multi-turn attacks by considering their support in jailbreak attacks and based on this propose a context-based contextual fusion black-box jailbreak attack method named Context Fusion Attack (CFA). This method approach involves filtering and extracting key terms from the target constructing contextual scenarios around these terms dynamically integrating the target into the scenarios replacing malicious key terms within the target and thereby concealing the direct malicious intent. Through comparisons on various mainstream LLMs and red team datasets we have demonstrated CFAs superior success rate divergence and harmfulness compared to other multi-turn attack strategies particularly showcasing significant advantages on Llama3 and GPT-4.
