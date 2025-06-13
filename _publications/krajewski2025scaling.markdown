---
layout: publication
title: 'Scaling Fine-grained Moe Beyond 50B Parameters: Empirical Evaluation And Practical Insights'
authors: Jakub Krajewski, Marcin Chochowski, Daniel Korzekwa
conference: "Arxiv"
year: 2025
bibkey: krajewski2025scaling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02890'}
tags: ['Training Techniques', 'RAG', 'Model Architecture']
---
Mixture of Experts (MoE) architectures have emerged as pivotal for scaling Large Language Models (LLMs) efficiently. Fine-grained MoE approaches - utilizing more numerous, smaller experts - have demonstrated potential in improving model convergence and quality. This work proposes a set of training recipes and provides a comprehensive empirical evaluation of fine-grained MoE, directly comparing its scaling properties against standard MoE configurations for models with up to 56B total (17B active) parameters. We investigate convergence speed, model performance on downstream benchmarks, and practical training considerations across various setups. Overall, at the largest scale we show that fine-grained MoE achieves better validation loss and higher accuracy across a set of downstream benchmarks. This study offers empirical grounding and practical insights for leveraging fine-grained MoE in the development of future large-scale models.
