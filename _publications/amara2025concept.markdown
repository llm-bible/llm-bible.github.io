---
layout: publication
title: 'Concept-level Explainability For Auditing & Steering LLM Responses'
authors: Kenza Amara, Rita Sevastjanova, Mennatallah El-assady
conference: "Arxiv"
year: 2025
bibkey: amara2025concept
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07610"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Reinforcement Learning', 'Language Modeling', 'Ethics and Bias', 'Interpretability', 'Interpretability and Explainability', 'Prompting', 'Applications']
---
As large language models (LLMs) become widely deployed, concerns about their safety and alignment grow. An approach to steer LLM behavior, such as mitigating biases or defending against jailbreaks, is to identify which parts of a prompt influence specific aspects of the model's output. Token-level attribution methods offer a promising solution, but still struggle in text generation, explaining the presence of each token in the output separately, rather than the underlying semantics of the entire LLM response. We introduce ConceptX, a model-agnostic, concept-level explainability method that identifies the concepts, i.e., semantically rich tokens in the prompt, and assigns them importance based on the outputs' semantic similarity. Unlike current token-level methods, ConceptX also offers to preserve context integrity through in-place token replacements and supports flexible explanation goals, e.g., gender bias. ConceptX enables both auditing, by uncovering sources of bias, and steering, by modifying prompts to shift the sentiment or reduce the harmfulness of LLM responses, without requiring retraining. Across three LLMs, ConceptX outperforms token-level methods like TokenSHAP in both faithfulness and human alignment. Steering tasks boost sentiment shift by 0.252 versus 0.131 for random edits and lower attack success rates from 0.463 to 0.242, outperforming attribution and paraphrasing baselines. While prompt engineering and self-explaining methods sometimes yield safer responses, ConceptX offers a transparent and faithful alternative for improving LLM safety and alignment, demonstrating the practical value of attribution-based explainability in guiding LLM behavior.
