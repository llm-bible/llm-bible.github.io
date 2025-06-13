---
layout: publication
title: 'Threading The Needle: Reweaving Chain-of-thought Reasoning To Explain Human Label Variation'
authors: Beiduo Chen, Yang Janet Liu, Anna Korhonen, Barbara Plank
conference: "Arxiv"
year: 2025
bibkey: chen2025threading
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23368"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'Interpretability and Explainability', 'Attention Mechanism']
---
The recent rise of reasoning-tuned Large Language Models (LLMs)--which generate chains of thought (CoTs) before giving the final answer--has attracted significant attention and offers new opportunities for gaining insights into human label variation, which refers to plausible differences in how multiple annotators label the same data instance. Prior work has shown that LLM-generated explanations can help align model predictions with human label distributions, but typically adopt a reverse paradigm: producing explanations based on given answers. In contrast, CoTs provide a forward reasoning path that may implicitly embed rationales for each answer option, before generating the answers. We thus propose a novel LLM-based pipeline enriched with linguistically-grounded discourse segmenters to extract supporting and opposing statements for each answer option from CoTs with improved accuracy. We also propose a rank-based HLV evaluation framework that prioritizes the ranking of answers over exact scores, which instead favor direct comparison of label distributions. Our method outperforms a direct generation method as well as baselines on three datasets, and shows better alignment of ranking methods with humans, highlighting the effectiveness of our approach.
