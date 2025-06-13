---
layout: publication
title: 'The Pragmatic Mind Of Machines: Tracing The Emergence Of Pragmatic Competence In Large Language Models'
authors: Kefan Yu, Qingcheng Zeng, Weihao Xuan, Wanxin Li, Jingyi Wu, Rob Voigt
conference: "Arxiv"
year: 2025
bibkey: yu2025pragmatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18497"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'Tools', 'RAG', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Pretraining Methods']
---
Current large language models (LLMs) have demonstrated emerging capabilities in social intelligence tasks, including implicature resolution (Sravanthi et al. (2024)) and theory-of-mind reasoning (Shapira et al. (2024)), both of which require substantial pragmatic understanding. However, how LLMs acquire this competence throughout the training process remains poorly understood. In this work, we introduce ALTPRAG, a dataset grounded in the pragmatic concept of alternatives, designed to evaluate whether LLMs at different training stages can accurately infer nuanced speaker intentions. Each instance pairs two contextually appropriate but pragmatically distinct continuations, enabling fine-grained assessment of both pragmatic interpretation and contrastive reasoning. We systematically evaluate 22 LLMs across key training stages: pre-training, supervised fine-tuning (SFT), and preference optimization, to examine the development of pragmatic competence. Our results show that even base models exhibit notable sensitivity to pragmatic cues, which improves consistently with increases in model and data scale. Additionally, SFT and RLHF contribute further gains, particularly in cognitive-pragmatic reasoning. These findings highlight pragmatic competence as an emergent and compositional property of LLM training and offer new insights for aligning models with human communicative norms.
