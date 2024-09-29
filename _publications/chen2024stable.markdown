---
layout: publication
title: SATO Stable Text-to-motion Framework
authors: Chen Wenshuo, Xiao Hongru, Zhang Erhang, Hu Lijie, Wang Lei, Liu Mengyuan, Chen Chen
conference: "Arxiv"
year: 2024
bibkey: chen2024stable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01461"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Is the Text to Motion model robust Recent advancements in Text to Motion models primarily stem from more accurate predictions of specific actions. However the text modality typically relies solely on pre-trained Contrastive Language-Image Pretraining (CLIP) models. Our research has uncovered a significant issue with the text-to-motion model its predictions often exhibit inconsistent outputs resulting in vastly different or even incorrect poses when presented with semantically similar or identical text inputs. In this paper we undertake an analysis to elucidate the underlying causes of this instability establishing a clear link between the unpredictability of model outputs and the erratic attention patterns of the text encoder module. Consequently we introduce a formal framework aimed at addressing this issue which we term the Stable Text-to-Motion Framework (SATO). SATO consists of three modules each dedicated to stable attention stable prediction and maintaining a balance between accuracy and robustness trade-off. We present a methodology for constructing an SATO that satisfies the stability of attention and prediction. To verify the stability of the model we introduced a new textual synonym perturbation dataset based on HumanML3D and KIT-ML. Results show that SATO is significantly more stable against synonyms and other slight perturbations while keeping its high accuracy performance.
