---
layout: publication
title: Transferring Troubles: Cross-lingual Transferability Of Backdoor Attacks In Llms With Instruction Tuning
authors: He Xuanli, Wang Jun, Xu Qiongkai, Minervini Pasquale, Stenetorp Pontus, Rubinstein Benjamin I. P., Cohn Trevor
conference: "Arxiv"
year: 2024
bibkey: he2024transferring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.19597"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
The implications of backdoor attacks on English-centric large language models (LLMs) have been widely examined - such attacks can be achieved by embedding malicious behaviors during training and activated under specific conditions that trigger malicious outputs. However the impact of backdoor attacks on multilingual models remains under-explored. Our research focuses on cross-lingual backdoor attacks against multilingual LLMs particularly investigating how poisoning the instruction-tuning data in one or two languages can affect the outputs in languages whose instruction-tuning data was not poisoned. Despite its simplicity our empirical analysis reveals that our method exhibits remarkable efficacy in models like mT5 BLOOM and GPT-3.5-turbo with high attack success rates surpassing 9537; in several languages across various scenarios. Alarmingly our findings also indicate that larger models show increased susceptibility to transferable cross-lingual backdoor attacks which also applies to LLMs predominantly pre-trained on English data such as Llama2 Llama3 and Gemma. Moreover our experiments show that triggers can still work even after paraphrasing and the backdoor mechanism proves highly effective in cross-lingual response settings across 25 languages achieving an average attack success rate of 5037;. Our study aims to highlight the vulnerabilities and significant security risks present in current multilingual LLMs underscoring the emergent need for targeted security measures.
