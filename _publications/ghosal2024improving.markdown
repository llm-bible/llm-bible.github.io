---
layout: publication
title: 'Immune: Improving Safety Against Jailbreaks In Multi-modal Llms Via Inference-time Alignment'
authors: Soumya Suvra Ghosal, Souradip Chakraborty, Vaibhav Singh, Tianrui Guan, Mengdi Wang, Alvaro Velasquez, Ahmad Beirami, Furong Huang, Dinesh Manocha, Amrit Singh Bedi
conference: "Arxiv"
year: 2024
bibkey: ghosal2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18688"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG']
---
With the widespread deployment of Multimodal Large Language Models (MLLMs) for visual-reasoning tasks, improving their safety has become crucial. Recent research indicates that despite training-time safety alignment, these models remain vulnerable to jailbreak attacks. In this work, we first highlight an important safety gap to describe that alignment achieved solely through safety training may be insufficient against jailbreak attacks. To address this vulnerability, we propose Immune, an inference-time defense framework that leverages a safe reward model through controlled decoding to defend against jailbreak attacks. Additionally, we provide a mathematical characterization of Immune, offering insights on why it improves safety against jailbreaks. Extensive evaluations on diverse jailbreak benchmarks using recent MLLMs reveal that Immune effectively enhances model safety while preserving the model's original capabilities. For instance, against text-based jailbreak attacks on LLaVA-1.6, Immune reduces the attack success rate by 57.82% and 16.78% compared to the base MLLM and state-of-the-art defense strategy, respectively.
