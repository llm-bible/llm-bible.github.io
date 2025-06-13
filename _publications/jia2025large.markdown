---
layout: publication
title: 'Large Language Model Strategic Reasoning Evaluation Through Behavioral Game Theory'
authors: Jingru Jia, Zehua Yuan, Junhao Pan, Paul E. Mcnamara, Deming Chen
conference: "Arxiv"
year: 2025
bibkey: jia2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20432"}
tags: ['Agentic', 'Model Architecture', 'Fairness', 'Tools', 'Reinforcement Learning', 'GPT', 'Bias Mitigation', 'Ethics and Bias', 'Prompting']
---
Strategic decision-making involves interactive reasoning where agents adapt
their choices in response to others, yet existing evaluations of large language
models (LLMs) often emphasize Nash Equilibrium (NE) approximation, overlooking
the mechanisms driving their strategic choices. To bridge this gap, we
introduce an evaluation framework grounded in behavioral game theory,
disentangling reasoning capability from contextual effects. Testing 22
state-of-the-art LLMs, we find that GPT-o3-mini, GPT-o1, and DeepSeek-R1
dominate most games yet also demonstrate that the model scale alone does not
determine performance. In terms of prompting enhancement, Chain-of-Thought
(CoT) prompting is not universally effective, as it increases strategic
reasoning only for models at certain levels while providing limited gains
elsewhere. Additionally, we investigate the impact of encoded demographic
features on the models, observing that certain assignments impact the
decision-making pattern. For instance, GPT-4o shows stronger strategic
reasoning with female traits than males, while Gemma assigns higher reasoning
levels to heterosexual identities compared to other sexual orientations,
indicating inherent biases. These findings underscore the need for ethical
standards and contextual alignment to balance improved reasoning with fairness.
