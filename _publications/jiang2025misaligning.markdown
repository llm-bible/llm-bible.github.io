---
layout: publication
title: 'Misaligning Reasoning With Answers -- A Framework For Assessing LLM Cot Robustness'
authors: Enyi Jiang, Changming Xu, Nischay Singh, Gagandeep Singh
conference: "Arxiv"
year: 2025
bibkey: jiang2025misaligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17406"}
tags: ['Security', 'Model Architecture', 'Tools', 'Interpretability and Explainability', 'Prompting']
---
LLMs' decision-making process is opaque, prompting the need for explanation techniques like Chain-of-Thought. To investigate the relationship between answer and reasoning, we design a novel evaluation framework, MATCHA. In domains like education and healthcare, reasoning is key for model trustworthiness. MATCHA reveals that LLMs under input perturbations can give inconsistent or nonsensical reasoning. Additionally, we use LLM judges to assess reasoning robustness across models. Our results show that LLMs exhibit greater vulnerability to input perturbations for multi-step and commonsense tasks than compared to logical tasks. Also, we show non-trivial transfer rates of our successful examples to black-box models. Our evaluation framework helps to better understand LLM reasoning mechanisms and guides future models toward more robust and reasoning-driven architectures, enforcing answer-reasoning consistency.
