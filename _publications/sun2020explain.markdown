---
layout: publication
title: 'Explain And Improve: Lrp-inference Fine-tuning For Image Captioning Models'
authors: Sun Jiamei, Lapuschkin Sebastian, Samek Wojciech, Binder Alexander
conference: "Arxiv"
year: 2020
bibkey: sun2020explain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2001.01037"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
This paper analyzes the predictions of image captioning models with attention mechanisms beyond visualizing the attention itself. We develop variants of layer-wise relevance propagation (LRP) and gradient-based explanation methods, tailored to image captioning models with attention mechanisms. We compare the interpretability of attention heatmaps systematically against the explanations provided by explanation methods such as LRP, Grad-CAM, and Guided Grad-CAM. We show that explanation methods provide simultaneously pixel-wise image explanations (supporting and opposing pixels of the input image) and linguistic explanations (supporting and opposing words of the preceding sequence) for each word in the predicted captions. We demonstrate with extensive experiments that explanation methods 1) can reveal additional evidence used by the model to make decisions compared to attention; 2) correlate to object locations with high precision; 3) are helpful to debug the model, e.g. by analyzing the reasons for hallucinated object words. With the observed properties of explanations, we further design an LRP-inference fine-tuning strategy that reduces the issue of object hallucination in image captioning models, and meanwhile, maintains the sentence fluency. We conduct experiments with two widely used attention mechanisms: the adaptive attention mechanism calculated with the additive attention and the multi-head attention mechanism calculated with the scaled dot product.
