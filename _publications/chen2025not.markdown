---
layout: publication
title: 'Not All Lora Parameters Are Essential: Insights On Inference Necessity'
authors: Guanhua Chen, Yutong Yao, Ci-jun Gao, Lidia S. Chao, Feng Wan, Derek F. Wong
conference: "Arxiv"
year: 2025
bibkey: chen2025not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23360"}
tags: ['Language Modeling', 'Model Architecture', 'Applications', 'Fine-Tuning']
---
Current research on LoRA primarily focuses on minimizing the number of
fine-tuned parameters or optimizing its architecture. However, the necessity of
all fine-tuned LoRA layers during inference remains underexplored. In this
paper, we investigate the contribution of each LoRA layer to the model's
ability to predict the ground truth and hypothesize that lower-layer LoRA
modules play a more critical role in model reasoning and understanding. To
address this, we propose a simple yet effective method to enhance the
performance of large language models (LLMs) fine-tuned with LoRA. Specifically,
we identify a ``boundary layer'' that distinguishes essential LoRA layers by
analyzing a small set of validation samples. During inference, we drop all LoRA
layers beyond this boundary. We evaluate our approach on three strong baselines
across four widely-used text generation datasets. Our results demonstrate
consistent and significant improvements, underscoring the effectiveness of
selectively retaining critical LoRA layers during inference.
