---
layout: publication
title: 'Llm-based Semantic Augmentation For Harmful Content Detection'
authors: Elyas Meguellati, Assaad Zeghina, Shazia Sadiq, Gianluca Demartini
conference: "Arxiv"
year: 2025
bibkey: meguellati2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15548"}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Prompting', 'Reinforcement Learning']
---
Recent advances in large language models (LLMs) have demonstrated strong
performance on simple text classification tasks, frequently under zero-shot
settings. However, their efficacy declines when tackling complex social media
challenges such as propaganda detection, hateful meme classification, and
toxicity identification. Much of the existing work has focused on using LLMs to
generate synthetic training data, overlooking the potential of LLM-based text
preprocessing and semantic augmentation. In this paper, we introduce an
approach that prompts LLMs to clean noisy text and provide context-rich
explanations, thereby enhancing training sets without substantial increases in
data volume. We systematically evaluate on the SemEval 2024 multi-label
Persuasive Meme dataset and further validate on the Google Jigsaw toxic
comments and Facebook hateful memes datasets to assess generalizability. Our
results reveal that zero-shot LLM classification underperforms on these
high-context tasks compared to supervised models. In contrast, integrating
LLM-based semantic augmentation yields performance on par with approaches that
rely on human-annotated data, at a fraction of the cost. These findings
underscore the importance of strategically incorporating LLMs into machine
learning (ML) pipeline for social media classification tasks, offering broad
implications for combating harmful content online.
