---
layout: publication
title: 'Transferable Speech-to-text Large Language Model Alignment Module'
authors: Wu Boyong, Yan Chao, Pu Haoran
conference: "Arxiv"
year: 2024
bibkey: wu2024transferable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13357"}
tags: ['Applications', 'Model Architecture', 'RAG']
---
By leveraging the power of Large Language Models(LLMs) and speech foundation models state of the art speech-text bimodal works can achieve challenging tasks like spoken translation(ST) and question answering(SQA) altogether with much simpler architectures. In this paper we utilize the capability of Whisper encoder and pre-trained Yi-6B. Empirical results reveal that modal alignment can be achieved with one layer module and hundred hours of speech-text multitask corpus. We further swap the Yi-6B with human preferences aligned version of Yi-6B-Chat during inference and discover that the alignment capability is applicable as well. In addition the alignment subspace revealed by singular value decomposition(SVD) also implies linear alignment subspace is sparse which leaves the possibility to concatenate other features like voice-print or video to expand modality.
