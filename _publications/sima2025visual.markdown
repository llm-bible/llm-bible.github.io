---
layout: publication
title: 'Viscra: A Visual Chain Reasoning Attack For Jailbreaking Multimodal Large Language Models'
authors: Bingrui Sima, Linhua Cong, Wenxuan Wang, Kun He
conference: "Arxiv"
year: 2025
bibkey: sima2025visual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19684'}
tags: ['Attention Mechanism', 'Agentic', 'Security', 'Model Architecture', 'Tools', 'GPT', 'Multimodal Models', 'Reinforcement Learning', 'Responsible AI']
---
The emergence of Multimodal Large Language Models (MLRMs) has enabled sophisticated visual reasoning capabilities by integrating reinforcement learning and Chain-of-Thought (CoT) supervision. However, while these enhanced reasoning capabilities improve performance, they also introduce new and underexplored safety risks. In this work, we systematically investigate the security implications of advanced visual reasoning in MLRMs. Our analysis reveals a fundamental trade-off: as visual reasoning improves, models become more vulnerable to jailbreak attacks. Motivated by this critical finding, we introduce VisCRA (Visual Chain Reasoning Attack), a novel jailbreak framework that exploits the visual reasoning chains to bypass safety mechanisms. VisCRA combines targeted visual attention masking with a two-stage reasoning induction strategy to precisely control harmful outputs. Extensive experiments demonstrate VisCRA's significant effectiveness, achieving high attack success rates on leading closed-source MLRMs: 76.48% on Gemini 2.0 Flash Thinking, 68.56% on QvQ-Max, and 56.60% on GPT-4o. Our findings highlight a critical insight: the very capability that empowers MLRMs -- their visual reasoning -- can also serve as an attack vector, posing significant security risks.
