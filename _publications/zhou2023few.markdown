---
layout: publication
title: 'Flame: Few-shot Learning From Natural Language Explanations'
authors: Zhou Yangqiaoyu, Zhang Yiming, Tan Chenhao
conference: "Arxiv"
year: 2023
bibkey: zhou2023few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.08042"}
tags: ['BERT', 'Few Shot', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Tools', 'Uncategorized']
---
Natural language explanations have the potential to provide rich information that in principle guides model reasoning. Yet, recent work by Lampinen et al. (2022) has shown limited utility of natural language explanations in improving classification. To effectively learn from explanations, we present FLamE, a two-stage few-shot learning framework that first generates explanations using GPT-3, and then finetunes a smaller model (e.g., RoBERTa) with generated explanations. Our experiments on natural language inference demonstrate effectiveness over strong baselines, increasing accuracy by 17.6&#37; over GPT-3 Babbage and 5.7&#37; over GPT-3 Davinci in e-SNLI. Despite improving classification performance, human evaluation surprisingly reveals that the majority of generated explanations does not adequately justify classification decisions. Additional analyses point to the important role of label-specific cues (e.g., not know for the neutral label) in generated explanations.
