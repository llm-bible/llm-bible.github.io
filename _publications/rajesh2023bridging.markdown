---
layout: publication
title: Bridging The Gap\: Exploring The Capabilities Of Bridge-architectures For Complex Visual Reasoning Tasks
authors: Rajesh Kousik, Raman Mrigank, Karim Mohammed Asad, Chawla Pranit
conference: "Arxiv"
year: 2023
bibkey: rajesh2023bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.16395"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
In recent times there has been a surge of multi-modal architectures based on Large Language Models which leverage the zero shot generation capabilities of LLMs and project image embeddings into the text space and then use the auto-regressive capacity to solve tasks such as VQA captioning and image retrieval. We name these architectures as bridge-architectures as they project from the image space to the text space. These models deviate from the traditional recipe of training transformer based multi-modal models which involve using large-scale pre-training and complex multi-modal interactions through co or cross attention. However the capabilities of bridge architectures have not been tested on complex visual reasoning tasks which require fine grained analysis about the image. In this project we investigate the performance of these bridge-architectures on the NLVR2 dataset and compare it to state-of-the-art transformer based architectures. We first extend the traditional bridge architectures for the NLVR2 dataset by adding object level features to faciliate fine-grained object reasoning. Our analysis shows that adding object level features to bridge architectures does not help and that pre-training on multi-modal data is key for good performance on complex reasoning tasks such as NLVR2. We also demonstrate some initial results on a recently bridge-architecture LLaVA in the zero shot setting and analyze its performance.
