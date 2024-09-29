---
layout: publication
title: Augmenting Math Word Problems Via Iterative Question Composing
authors: Liu Haoxiong, Zhang Yifan, Luo Yifan, Yao Andrew Chi-chih
conference: "Arxiv"
year: 2024
bibkey: liu2024augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.09003"}
  - {name: "Code", url: "https://huggingface.co/datasets/Vivacem/MMIQC"}
  - {name: "Code", url: "https://github.com/iiis&#45;ai/IterativeQuestionComposing"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
Despite the advancements in large language models (LLMs) for mathematical reasoning solving competition45;level math problems remains a significant challenge especially for open45;source LLMs without external tools. We introduce the MMIQC dataset comprising a mixture of processed web data and synthetic question45;response pairs aimed at enhancing the mathematical reasoning capabilities of base language models. Models fine45;tuned on MMIQC consistently surpass their counterparts in performance on the MATH benchmark across various model sizes. Notably Qwen45;72B45;MMIQC achieves a 45.037; accuracy exceeding the previous open45;source state45;of45;the45;art by 8.237; and outperforming the initial version GPT45;4 released in 2023. Extensive evaluation results on Hungarian high school finals suggest that such improvement can generalize to unseen data. Our ablation study on MMIQC reveals that a large part of the improvement can be attributed to our novel augmentation method Iterative Question Composing (IQC) which involves iteratively composing new questions from seed problems using an LLM and applying rejection sampling through another LLM. The MMIQC dataset is available on the HuggingFace hub at https://huggingface.co/datasets/Vivacem/MMIQC. Our code is available at https://github.com/iiis&#45;ai/IterativeQuestionComposing.
