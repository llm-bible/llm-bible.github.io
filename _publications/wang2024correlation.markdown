---
layout: publication
title: 'Correlation-aware Select And Merge Attention For Efficient Fine-tuning And Context Length Extension'
authors: Ning Wang, Zekun Li, Tongxin Bai, Guoqi Li
conference: "Arxiv"
year: 2024
bibkey: wang2024correlation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04211"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Model Architecture', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Modeling long sequences is crucial for various large-scale models; however,
extending existing architectures to handle longer sequences presents
significant technical and resource challenges. In this paper, we propose an
efficient and flexible attention architecture that enables the extension of
context lengths in large language models with reduced computational resources
and fine-tuning time compared to other excellent methods. Specifically, we
introduce correlation-aware selection and merging mechanisms to facilitate
efficient sparse attention. In addition, we also propose a novel data
augmentation technique involving positional encodings to enhance generalization
to unseen positions. The results are as follows: First, using a single A100, we
achieve fine-tuning on Llama2-7B with a sequence length of 32K, which is more
efficient than other methods that rely on subsets for regression. Second, we
present a comprehensive method for extending context lengths across the
pre-training, fine-tuning, and inference phases. During pre-training, our
attention mechanism partially breaks translation invariance during token
selection, so we apply positional encodings only to the selected tokens. This
approach achieves relatively high performance and significant extrapolation
capabilities. For fine-tuning, we introduce Cyclic, Randomly Truncated, and
Dynamically Growing NTK Positional Embedding (CRD NTK). This design allows
fine-tuning with a sequence length of only 16K, enabling models such as
Llama2-7B and Mistral-7B to perform inference with context lengths of up to 1M
or even arbitrary lengths. Our method achieves 100% accuracy on the passkey
task with a context length of 4M and maintains stable perplexity at a 1M
context length. This represents at least a 64-fold reduction in resource
requirements compared to traditional full-attention mechanisms, while still
achieving competitive performance.
