---
layout: publication
title: 'Commitbart: A Large Pre-trained Model For Github Commits'
authors: Liu Shangqing, Li Yanzhou, Xie Xiaofei, Liu Yang
conference: "Arxiv"
year: 2022
bibkey: liu2022large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.08100"}
tags: ['Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
GitHub commits which record the code changes with natural language messages for description play a critical role for software developers to comprehend the software evolution. To promote the development of the open-source software community we collect a commit benchmark including over 7.99 million commits across 7 programming languages. Based on this benchmark we present CommitBART a large pre-trained encoder-decoder Transformer model for GitHub commits. The model is pre-trained by three categories (i.e. denoising objectives cross-modal generation and contrastive learning) for six pre-training tasks to learn commit fragment representations. Furthermore we unify a commit intelligence framework with one understanding task and three generation tasks for commits. The comprehensive experiments on these tasks demonstrate that CommitBARTsignificantly outperforms previous pre-trained works for code. Further analysis also reveals each pre-training task enhances the model performance.
