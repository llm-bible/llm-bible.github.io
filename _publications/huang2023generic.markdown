---
layout: publication
title: Generic Attention45;model Explainability By Weighted Relevance Accumulation
authors: Huang Yiming, Jia Aozhe, Zhang Xiaodan, Zhang Jiawei
conference: "Arxiv"
year: 2023
bibkey: huang2023generic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.10240"}
tags: ['Applications', 'Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Attention45;based transformer models have achieved remarkable progress in multi45;modal tasks such as visual question answering. The explainability of attention45;based methods has recently attracted wide interest as it can explain the inner changes of attention tokens by accumulating relevancy across attention layers. Current methods simply update relevancy by equally accumulating the token relevancy before and after the attention processes. However the importance of token values is usually different during relevance accumulation. In this paper we propose a weighted relevancy strategy which takes the importance of token values into consideration to reduce distortion when equally accumulating relevance. To evaluate our method we propose a unified CLIP45;based two45;stage model named CLIPmapper to process Vision45;and45;Language tasks through CLIP encoder and a following mapper. CLIPmapper consists of self45;attention cross45;attention single45;modality and cross45;modality attention thus it is more suitable for evaluating our generic explainability method. Extensive perturbation tests on visual question answering and image captioning validate that our explainability method outperforms existing methods.
