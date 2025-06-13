---
layout: publication
title: 'CODI: Compressing Chain-of-thought Into Continuous Space Via Self-distillation'
authors: Zhenyi Shen, Hanqi Yan, Linhai Zhang, Zhanghao Hu, Yali Du, Yulan He
conference: "Arxiv"
year: 2025
bibkey: shen2025compressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.21074"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'RAG', 'Distillation', 'GPT', 'Interpretability and Explainability']
---
Chain-of-Thought (CoT) reasoning enhances Large Language Models (LLMs) by encouraging step-by-step reasoning in natural language. However, leveraging a latent continuous space for reasoning may offer benefits in terms of both efficiency and robustness. Prior implicit CoT methods attempt to bypass language completely by reasoning in continuous space but have consistently underperformed compared to the standard explicit CoT approach. We introduce CODI (Continuous Chain-of-Thought via Self-Distillation), a novel training framework that effectively compresses natural language CoT into continuous space. CODI jointly trains a teacher task (Explicit CoT) and a student task (Implicit CoT), distilling the reasoning ability from language into continuous space by aligning the hidden states of a designated token. Our experiments show that CODI is the first implicit CoT approach to match the performance of explicit CoT on GSM8k at the GPT-2 scale, achieving a 3.1x compression rate and outperforming the previous state-of-the-art by 28.2% in accuracy. CODI also demonstrates robustness, generalizable to complex datasets, and interpretability. These results validate that LLMs can reason effectively not only in natural language, but also in a latent continuous space.
