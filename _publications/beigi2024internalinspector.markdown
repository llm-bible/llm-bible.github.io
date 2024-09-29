---
layout: publication
title: 'Internalinspector $I^2$: Robust Confidence Estimation In Llms Through Internal States'
authors: Beigi Mohammad, Shen Ying, Yang Runing, Lin Zihao, Wang Qifan, Mohan Ankith, He Jianfeng, Jin Ming, Lu Chang-tien, Huang Lifu
conference: "Arxiv"
year: 2024
bibkey: beigi2024internalinspector
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12053"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools']
---
Despite their vast capabilities Large Language Models (LLMs) often struggle with generating reliable outputs frequently producing high-confidence inaccuracies known as hallucinations. Addressing this challenge our research introduces InternalInspector a novel framework designed to enhance confidence estimation in LLMs by leveraging contrastive learning on internal states including attention states feed-forward states and activation states of all layers. Unlike existing methods that primarily focus on the final activation state InternalInspector conducts a comprehensive analysis across all internal states of every layer to accurately identify both correct and incorrect prediction processes. By benchmarking InternalInspector against existing confidence estimation methods across various natural language understanding and generation tasks including factual question answering commonsense reasoning and reading comprehension InternalInspector achieves significantly higher accuracy in aligning the estimated confidence scores with the correctness of the LLMs predictions and lower calibration error. Furthermore InternalInspector excels at HaluEval a hallucination detection benchmark outperforming other internal-based confidence estimation methods in this task.
