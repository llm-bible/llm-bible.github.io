---
layout: publication
title: SPDF&#58; Sparse Pre-training And Dense Fine-tuning For Large Language Models
authors: Thangarasa Vithursan, Gupta Abhay, Marshall William, Li Tianda, Leong Kevin, Decoste Dennis, Lie Sean, Saxena Shreyas
conference: "Arxiv"
year: 2023
bibkey: thangarasa2023sparse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.10464"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
The pre-training and fine-tuning paradigm has contributed to a number of breakthroughs in Natural Language Processing (NLP). Instead of directly training on a downstream task language models are first pre-trained on large datasets with cross-domain knowledge (e.g. Pile MassiveText etc.) and then fine-tuned on task-specific data (e.g. natural language generation text summarization etc.). Scaling the model and dataset size has helped improve the performance of LLMs but unfortunately this also lead to highly prohibitive computational costs. Pre-training LLMs often require orders of magnitude more FLOPs than fine-tuning and the model capacity often remains the same between the two phases. To achieve training efficiency w.r.t training FLOPs we propose to decouple the model capacity between the two phases and introduce Sparse Pre-training and Dense Fine-tuning (SPDF). In this work we show the benefits of using unstructured weight sparsity to train only a subset of weights during pre-training (Sparse Pre-training) and then recover the representational capacity by allowing the zeroed weights to learn (Dense Fine-tuning). We demonstrate that we can induce up to 7537; sparsity into a 1.3B parameter GPT-3 XL model resulting in a 2.5x reduction in pre-training FLOPs without a significant loss in accuracy on the downstream tasks relative to the dense baseline. By rigorously evaluating multiple downstream tasks we also establish a relationship between sparsity task complexity and dataset size. Our work presents a promising direction to train large GPT models at a fraction of the training FLOPs using weight sparsity while retaining the benefits of pre-trained textual representations for downstream tasks.
