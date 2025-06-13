---
layout: publication
title: 'Natural Language Planning Via Coding And Inference Scaling'
authors: Rikhil Amonkar, Ronan Le Bras, Li Zhang
conference: "Arxiv"
year: 2025
bibkey: amonkar2025natural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13252"}
tags: ['Security', 'Efficiency and Optimization']
---
Real-life textual planning tasks such as meeting scheduling have posed much challenge to LLMs especially when the complexity is high. While previous work primarily studied auto-regressive generation of plans with closed-source models, we systematically evaluate both closed- and open-source models, including those that scales output length with complexity during inference, in generating programs, which are executed to output the plan. We consider not only standard Python code, but also the code to a constraint satisfaction problem solver. Despite the algorithmic nature of the task, we show that programming often but not always outperforms planning. Our detailed error analysis also indicates a lack of robustness and efficiency in the generated code that hinders generalization.
