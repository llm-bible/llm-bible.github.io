---
layout: publication
title: Exploring Visual Interpretability For Contrastive Language-image Pre-training
authors: Li Yi, Wang Hualiang, Duan Yiqun, Xu Hang, Li Xiaomeng
conference: "Arxiv"
year: 2022
bibkey: li2022exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.07046"}
tags: ['Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Contrastive Language-Image Pre-training (CLIP) learns rich representations via readily available supervision of natural language. It improves the performance of downstream vision tasks including but not limited to the zero-shot long tail segmentation retrieval caption and video. However the visual explainability of CLIP is rarely studied especially for the raw feature map. To provide visual explanations of its predictions we propose the Image-Text Similarity Map (ITSM). Based on it we surprisingly find that CLIP prefers the background regions than the foregrounds and shows erroneous visualization results against human understanding. This phenomenon is universal for both vision transformers and convolutional networks which suggests this problem is unique and not owing to certain network. Experimentally we find the devil is in the pooling part where inappropriate pooling methods lead to a phenomenon called semantic shift. For this problem we propose the Explainable Contrastive Language-Image Pre-training (ECLIP) which corrects the explainability via the Masked Max Pooling. Specifically to avoid the semantic shift we replace the original attention pooling by max pooling to focus on the confident foreground with guidance from free attention during training. Experiments on three datasets suggest that ECLIP greatly improves the explainability of CLIP and beyond previous explainability methods at large margins. The code will be released later.
