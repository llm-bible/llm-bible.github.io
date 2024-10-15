---
layout: publication
title: 'Pandora: Jailbreak Gpts By Retrieval Augmented Generation Poisoning'
authors: Deng Gelei, Liu Yi, Wang Kailong, Li Yuekang, Zhang Tianwei, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: deng2024jailbreak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08416"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Uncategorized']
---
Large Language Models~(LLMs) have gained immense popularity and are being
increasingly applied in various domains. Consequently, ensuring the security of
these models is of paramount importance. Jailbreak attacks, which manipulate
LLMs to generate malicious content, are recognized as a significant
vulnerability. While existing research has predominantly focused on direct
jailbreak attacks on LLMs, there has been limited exploration of indirect
methods. The integration of various plugins into LLMs, notably Retrieval
Augmented Generation~(RAG), which enables LLMs to incorporate external
knowledge bases into their response generation such as GPTs, introduces new
avenues for indirect jailbreak attacks.
  To fill this gap, we investigate indirect jailbreak attacks on LLMs,
particularly GPTs, introducing a novel attack vector named Retrieval Augmented
Generation Poisoning. This method, Pandora, exploits the synergy between LLMs
and RAG through prompt manipulation to generate unexpected responses. Pandora
uses maliciously crafted content to influence the RAG process, effectively
initiating jailbreak attacks. Our preliminary tests show that Pandora
successfully conducts jailbreak attacks in four different scenarios, achieving
higher success rates than direct attacks, with 64.3% for GPT-3.5 and 34.8%
for GPT-4.
