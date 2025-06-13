---
layout: publication
title: 'Mask-enhanced Autoregressive Prediction: Pay Less Attention To Learn More'
authors: Xialie Zhuang, Zhikai Jia, Jianjin Li, Zhenyu Zhang, Li Shen, Zheng Cao, Shiwei Liu
conference: "Arxiv"
year: 2025
bibkey: zhuang2025mask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07490"}
tags: ['Masked Language Model', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'GPT', 'Pretraining Methods', 'BERT', 'Transformer', 'Fine-Tuning', 'Pre-Training', 'Applications', 'Attention Mechanism']
---
Large Language Models (LLMs) are discovered to suffer from accurately retrieving key information. To address this, we propose Mask-Enhanced Autoregressive Prediction (MEAP), a simple yet effective training paradigm that seamlessly integrates Masked Language Modeling (MLM) into Next-Token Prediction (NTP) to enhance the latter's in-context retrieval capabilities. Specifically, MEAP first randomly masks a small fraction of input tokens and then directly performs the standard next-token prediction autoregressive using a decoder-only Transformer. MEAP eliminates the need for bidirectional attention or encoder-decoder architectures for MLM, incurring no additional computational overhead during pre-training or inference. Intensive experiments demonstrate that MEAP substantially outperforms NTP on key information retrieval and long-context reasoning tasks, while performing on par or better on commonsense reasoning tasks. The benefits of MEAP also extend to supervised fine-tuning, where it shows remarkable advantages in lost-in-the-middle scenarios, outperforming NTP by 11.77 percentage points. Our analysis indicates that MEAP's effectiveness arises from its ability to promote more distinguishable attention scores by concentrating on a reduced set of non-masked tokens. This mechanism improves the model's focus on task-relevant signals while mitigating the influence of peripheral context. These findings position MEAP as a promising training paradigm for large language models.
