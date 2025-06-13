---
layout: publication
title: 'Large Language Models To Diffusion Finetuning'
authors: Edoardo Cetin, Tianyu Zhao, Yujin Tang
conference: "Arxiv"
year: 2025
bibkey: cetin2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15781"}
tags: ['Tools', 'RAG', 'Merging', 'GPT', 'Pretraining Methods']
---
We propose a new finetuning method to provide pre-trained large language models (LMs) the ability to scale test-time compute through the diffusion framework. By increasing the number of diffusion steps, we show our finetuned models achieve monotonically increasing accuracy, directly translating to improved performance across downstream tasks. Furthermore, our finetuned models can expertly answer questions on specific topics by integrating powerful guidance techniques, and autonomously determine the compute required for a given problem by leveraging adaptive ODE solvers. Our method is universally applicable to any foundation model pre-trained with a cross-entropy loss and does not modify any of its original weights, fully preserving its strong single-step generation capabilities. We show our method is more effective and fully compatible with traditional finetuning approaches, introducing an orthogonal new direction to unify the strengths of the autoregressive and diffusion frameworks.
