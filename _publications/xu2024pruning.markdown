---
layout: publication
title: BESA Pruning Large Language Models With Blockwise Parameter45;efficient Sparsity Allocation
authors: Xu Peng, Shao Wenqi, Chen Mengzhao, Tang Shitao, Zhang Kaipeng, Gao Peng, An Fengwei, Qiao Yu, Luo Ping
conference: "Arxiv"
year: 2024
bibkey: xu2024pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16880"}
  - {name: "Code", url: "https://github.com/OpenGVLab/LLMPrune&#45;BESA"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Transformer']
---
Large language models (LLMs) have demonstrated outstanding performance in various tasks such as text summarization text question45;answering and etc. While their performance is impressive the computational footprint due to their vast number of parameters can be prohibitive. Existing solutions such as SparseGPT and Wanda attempt to alleviate this issue through weight pruning. However their layer45;wise approach results in significant perturbation to the models output and requires meticulous hyperparameter tuning such as the pruning rate which can adversely affect overall model performance. To address this this paper introduces a novel LLM pruning technique dubbed blockwise parameter45;efficient sparsity allocation (BESA) by applying a blockwise reconstruction loss. In contrast to the typical layer45;wise pruning techniques BESA is characterized by two distinctive attributes i) it targets the overall pruning error with respect to individual transformer blocks and ii) it allocates layer45;specific sparsity in a differentiable manner both of which ensure reduced performance degradation after pruning. Our experiments show that BESA achieves state45;of45;the45;art performance efficiently pruning LLMs like LLaMA1 and LLaMA2 with 7B to 70B parameters on a single A100 GPU in just five hours. Code is available at https://github.com/OpenGVLab/LLMPrune&#45;BESA.
