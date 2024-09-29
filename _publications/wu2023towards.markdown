---
layout: publication
title: 'Towards Robust Text Retrieval With Progressive Learning'
authors: Wu Tong, Qin Yulei, Zhang Enwei, Xu Zihan, Gao Yuting, Li Ke, Sun Xing
conference: "Arxiv"
year: 2023
bibkey: wu2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11691"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Training Techniques']
---
Retrieval augmentation has become an effective solution to empower large language models (LLMs) with external and verified knowledge sources from the database which overcomes the limitations and hallucinations of LLMs in handling up-to-date and domain-specific information. However existing embedding models for text retrieval usually have three non-negligible limitations. First the number and diversity of samples in a batch are too restricted to supervise the modeling of textual nuances at scale. Second the high proportional noise are detrimental to the semantic correctness and consistency of embeddings. Third the equal treatment to easy and difficult samples would cause sub-optimum convergence of embeddings with poorer generalization. In this paper we propose the PEG a progressively learned embeddings for robust text retrieval. Specifically we increase the training in-batch negative samples to 80000 and for each query we extracted five hard negatives. Concurrently we incorporated a progressive learning mechanism enabling the model to dynamically modulate its attention to the samples throughout the entire training process. Additionally PEG is trained on more than 100 million data encompassing a wide range of domains (e.g. finance medicine and tourism) and covering various tasks (e.g. question-answering machine reading comprehension and similarity matching). Extensive experiments conducted on C-MTEB and DuReader demonstrate that PEG surpasses state-of-the-art embeddings in retrieving true positives highlighting its significant potential for applications in LLMs. Our model is publicly available at https://huggingface.co/TownsWu/PEG."
