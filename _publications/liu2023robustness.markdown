---
layout: publication
title: 'Robustness Over Time: Understanding Adversarial Examples'' Effectiveness On Longitudinal Versions Of Large Language Models'
authors: Liu Yugeng, Cong Tianshuo, Zhao Zhengyu, Backes Michael, Shen Yun, Zhang Yang
conference: "Arxiv"
year: 2023
bibkey: liu2023robustness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.07847"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security']
---
Large Language Models (LLMs) undergo continuous updates to improve user experience. However, prior research on the security and safety implications of LLMs has primarily focused on their specific versions, overlooking the impact of successive LLM updates. This prompts the need for a holistic understanding of the risks in these different versions of LLMs. To fill this gap, in this paper, we conduct a longitudinal study to examine the adversarial robustness -- specifically misclassification, jailbreak, and hallucination -- of three prominent LLMs: GPT-3.5, GPT-4, and LLaMA. Our study reveals that LLM updates do not consistently improve adversarial robustness as expected. For instance, a later version of GPT-3.5 degrades regarding misclassification and hallucination despite its improved resilience against jailbreaks, and GPT-4 demonstrates (incrementally) higher robustness overall. Moreover, larger model sizes do not necessarily yield improved robustness. Specifically, larger LLaMA models do not uniformly exhibit improved robustness across all three aspects studied. Importantly, minor updates lacking substantial robustness improvements can exacerbate existing issues rather than resolve them. By providing a more nuanced understanding of LLM robustness over time, we hope our study can offer valuable insights for developers and users navigating model updates and informed decisions in model development and usage for LLM vendors.
