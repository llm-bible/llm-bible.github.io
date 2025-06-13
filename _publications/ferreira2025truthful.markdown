---
layout: publication
title: 'Truthful Or Fabricated? Using Causal Attribution To Mitigate Reward Hacking In Explanations'
authors: Pedro Ferreira, Wilker Aziz, Ivan Titov
conference: "Arxiv"
year: 2025
bibkey: ferreira2025truthful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05294"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Ethics and Bias', 'Interpretability and Explainability', 'Reinforcement Learning']
---
Chain-of-thought explanations are widely used to inspect the decision process
of large language models (LLMs) and to evaluate the trustworthiness of model
outputs, making them important for effective collaboration between LLMs and
humans. We demonstrate that preference optimization - a key step in the
alignment phase - can inadvertently reduce the faithfulness of these
explanations. This occurs because the reward model (RM), which guides
alignment, is tasked with optimizing both the expected quality of the response
and the appropriateness of the explanations (e.g., minimizing bias or adhering
to safety standards), creating potential conflicts. The RM lacks a mechanism to
assess the consistency between the model's internal decision process and the
generated explanation. Consequently, the LLM may engage in "reward hacking" by
producing a final response that scores highly while giving an explanation
tailored to maximize reward rather than accurately reflecting its reasoning. To
address this issue, we propose enriching the RM's input with a causal
attribution of the prediction, allowing the RM to detect discrepancies between
the generated self-explanation and the model's decision process. In controlled
settings, we show that this approach reduces the tendency of the LLM to
generate misleading explanations.
