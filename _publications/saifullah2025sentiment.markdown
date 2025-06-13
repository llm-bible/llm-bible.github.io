---
layout: publication
title: 'Sentiment Analysis In Software Engineering: Evaluating Generative Pre-trained Transformers'
authors: Km Khalid Saifullah, Faiaz Azmain, Habiba Hye
conference: "Arxiv"
year: 2025
bibkey: saifullah2025sentiment
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14692"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
Sentiment analysis plays a crucial role in understanding developer interactions, issue resolutions, and project dynamics within software engineering (SE). While traditional SE-specific sentiment analysis tools have made significant strides, they often fail to account for the nuanced and context-dependent language inherent to the domain. This study systematically evaluates the performance of bidirectional transformers, such as BERT, against generative pre-trained transformers, specifically GPT-4o-mini, in SE sentiment analysis. Using datasets from GitHub, Stack Overflow, and Jira, we benchmark the models' capabilities with fine-tuned and default configurations. The results reveal that fine-tuned GPT-4o-mini performs comparable to BERT and other bidirectional models on structured and balanced datasets like GitHub and Jira, achieving macro-averaged F1-scores of 0.93 and 0.98, respectively. However, on linguistically complex datasets with imbalanced sentiment distributions, such as Stack Overflow, the default GPT-4o-mini model exhibits superior generalization, achieving an accuracy of 85.3% compared to the fine-tuned model's 13.1%. These findings highlight the trade-offs between fine-tuning and leveraging pre-trained models for SE tasks. The study underscores the importance of aligning model architectures with dataset characteristics to optimize performance and proposes directions for future research in refining sentiment analysis tools tailored to the SE domain.
