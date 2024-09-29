---
layout: publication
title: Contrastive Perplexity for Controlled Generation An Application in Detoxifying Large Language Models
authors: Klein Tassilo, Nabi Moin
conference: "Arxiv"
year: 2024
bibkey: klein2024contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08491"}
tags: ['Applications', 'Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
The generation of undesirable and factually incorrect content of large language models poses a significant challenge and remains largely an unsolved issue. This paper studies the integration of a contrastive learning objective for fine-tuning LLMs for implicit knowledge editing and controlled text generation. Optimizing the training objective entails aligning text perplexities in a contrastive fashion. To facilitate training the model in a self-supervised fashion we leverage an off-the-shelf LLM for training data generation. We showcase applicability in the domain of detoxification. Herein the proposed approach leads to a significant decrease in the generation of toxic content while preserving general utility for downstream tasks such as commonsense reasoning and reading comprehension. The proposed approach is conceptually simple but empirically powerful.
