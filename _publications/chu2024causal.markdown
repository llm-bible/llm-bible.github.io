---
layout: publication
title: A Causal Explainable Guardrails For Large Language Models
authors: Chu Zhixuan, Wang Yan, Li Longfei, Wang Zhibo, Qin Zhan, Ren Kui
conference: "Arxiv"
year: 2024
bibkey: chu2024causal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.04160"}
tags: ['Ethics And Bias', 'Prompting', 'Security', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have shown impressive performance in natural language tasks but their outputs can exhibit undesirable attributes or biases. Existing methods for steering LLMs toward desired attributes often assume unbiased representations and rely solely on steering prompts. However the representations learned from pre-training can introduce semantic biases that influence the steering process leading to suboptimal results. We propose LLMGuardrail a novel framework that incorporates causal analysis and adversarial learning to obtain unbiased steering representations in LLMs. LLMGuardrail systematically identifies and blocks the confounding effects of biases enabling the extraction of unbiased steering representations. Additionally it includes an explainable component that provides insights into the alignment between the generated output and the desired direction. Experiments demonstrate LLMGuardrails effectiveness in steering LLMs toward desired attributes while mitigating biases. Our work contributes to the development of safe and reliable LLMs that align with desired attributes.
