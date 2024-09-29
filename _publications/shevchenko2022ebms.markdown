---
layout: publication
title: Ebms Vs. CL Exploring Self45;supervised Visual Pretraining For Visual Question Answering
authors: Shevchenko Violetta, Abbasnejad Ehsan, Dick Anthony, Hengel Anton Van Den, Teney Damien
conference: "Arxiv"
year: 2022
bibkey: shevchenko2022ebms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.14355"}
tags: ['Applications', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Survey Paper', 'Training Techniques']
---
The availability of clean and diverse labeled data is a major roadblock for training models on complex tasks such as visual question answering (VQA). The extensive work on large vision45;and45;language models has shown that self45;supervised learning is effective for pretraining multimodal interactions. In this technical report we focus on visual representations. We review and evaluate self45;supervised methods to leverage unlabeled images and pretrain a model which we then fine45;tune on a custom VQA task that allows controlled evaluation and diagnosis. We compare energy45;based models (EBMs) with contrastive learning (CL). While EBMs are growing in popularity they lack an evaluation on downstream tasks. We find that both EBMs and CL can learn representations from unlabeled images that enable training a VQA model on very little annotated data. In a simple setting similar to CLEVR we find that CL representations also improve systematic generalization and even match the performance of representations from a larger supervised ImageNet45;pretrained model. However we find EBMs to be difficult to train because of instabilities and high variability in their results. Although EBMs prove useful for OOD detection other results on supervised energy45;based training and uncertainty calibration are largely negative. Overall CL currently seems a preferable option over EBMs.
