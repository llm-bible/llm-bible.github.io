---
layout: publication
title: Jailbreaking GPT-4V Via Self-adversarial Attacks With System Prompts
authors: Wu Yuanwei, Li Xiang, Liu Yixin, Zhou Pan, Sun Lichao
conference: "Arxiv"
year: 2023
bibkey: wu2023jailbreaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09127"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Security', 'Tools']
---
Existing work on jailbreak Multimodal Large Language Models (MLLMs) has focused primarily on adversarial examples in model inputs with less attention to vulnerabilities especially in model API. To fill the research gap we carry out the following work 1) We discover a system prompt leakage vulnerability in GPT-4V. Through carefully designed dialogue we successfully extract the internal system prompts of GPT-4V. This finding indicates potential exploitable security risks in MLLMs; 2) Based on the acquired system prompts we propose a novel MLLM jailbreaking attack method termed SASP (Self-Adversarial Attack via System Prompt). By employing GPT-4 as a red teaming tool against itself we aim to search for potential jailbreak prompts leveraging stolen system prompts. Furthermore in pursuit of better performance we also add human modification based on GPT-4s analysis which further improves the attack success rate to 98.737;; 3) We evaluated the effect of modifying system prompts to defend against jailbreaking attacks. Results show that appropriately designed system prompts can significantly reduce jailbreak success rates. Overall our work provides new insights into enhancing MLLM security demonstrating the important role of system prompts in jailbreaking. This finding could be leveraged to greatly facilitate jailbreak success rates while also holding the potential for defending against jailbreaks.
