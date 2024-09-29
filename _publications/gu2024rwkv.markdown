---
layout: publication
title: RWKV45;CLIP A Robust Vision45;language Representation Learner
authors: Gu Tiancheng, Yang Kaicheng, An Xiang, Feng Ziyong, Liu Dongnan, Cai Weidong, Deng Jiankang
conference: "Arxiv"
year: 2024
bibkey: gu2024rwkv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06973"}
  - {name: "Code", url: "https://github.com/deepglint/RWKV&#45;CLIP"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Contrastive Language45;Image Pre45;training (CLIP) has significantly improved performance in various vision45;language tasks by expanding the dataset with image45;text pairs obtained from websites. This paper further explores CLIP from the perspectives of data and model architecture. To address the prevalence of noisy data and enhance the quality of large45;scale image45;text data crawled from the internet we introduce a diverse description generation framework that can leverage Large Language Models (LLMs) to synthesize and refine content from web45;based texts synthetic captions and detection tags. Furthermore we propose RWKV45;CLIP the first RWKV45;driven vision45;language representation learning model that combines the effective parallel training of transformers with the efficient inference of RNNs. Comprehensive experiments across various model scales and pre45;training datasets demonstrate that RWKV45;CLIP is a robust and efficient vision45;language representation learner it achieves state45;of45;the45;art performance in several downstream tasks including linear probe zero45;shot classification and zero45;shot image45;text retrieval. To facilitate future research the code and pre45;trained models are released at https://github.com/deepglint/RWKV&#45;CLIP
