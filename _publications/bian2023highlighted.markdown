---
layout: publication
title: Helm&#58; Highlighted Evidence Augmented Language Model For Enhanced Table-to-text Generation
authors: Bian Junyi, Qin Xiaolei, Zou Wuhe, Huang Mengzuo, Luo Congyi, Zhang Ke, Zhang Weidong
conference: "Arxiv"
year: 2023
bibkey: bian2023highlighted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08896"}
tags: ['Applications', 'Fine Tuning', 'Interpretability And Explainability', 'Language Modeling', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large models have demonstrated significant progress across various domains particularly in tasks related to text generation. In the domain of Table to Text many Large Language Model (LLM)-based methods currently resort to modifying prompts to invoke public APIs incurring potential costs and information leaks. With the advent of open-source large models fine-tuning LLMs has become feasible. In this study we conducted parameter-efficient fine-tuning on the LLaMA2 model. Distinguishing itself from previous fine-tuning-based table-to-text methods our approach involves injecting reasoning information into the input by emphasizing table-specific row data. Our model consists of two modules 1) a table reasoner that identifies relevant row evidence and 2) a table summarizer that generates sentences based on the highlighted table. To facilitate this we propose a search strategy to construct reasoning labels for training the table reasoner. On both the FetaQA and QTSumm datasets our approach achieved state-of-the-art results. Additionally we observed that highlighting input tables significantly enhances the models performance and provides valuable interpretability.
