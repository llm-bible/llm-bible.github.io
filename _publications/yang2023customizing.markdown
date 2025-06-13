---
layout: publication
title: 'Customizing General-purpose Foundation Models For Medical Report Generation'
authors: Bang Yang, Asif Raza, Yuexian Zou, Tong Zhang
conference: "Arxiv"
year: 2023
bibkey: yang2023customizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.05642'}
tags: ['Transformer', 'Training Techniques', 'BERT', 'Model Architecture', 'Fine-Tuning', 'Multimodal Models', 'Pre-Training', 'Pretraining Methods']
---
Medical caption prediction which can be regarded as a task of medical report
generation (MRG), requires the automatic generation of coherent and accurate
captions for the given medical images. However, the scarcity of labelled
medical image-report pairs presents great challenges in the development of deep
and large-scale neural networks capable of harnessing the potential artificial
general intelligence power like large language models (LLMs). In this work, we
propose customizing off-the-shelf general-purpose large-scale pre-trained
models, i.e., foundation models (FMs), in computer vision and natural language
processing with a specific focus on medical report generation. Specifically,
following BLIP-2, a state-of-the-art vision-language pre-training approach, we
introduce our encoder-decoder-based MRG model. This model utilizes a
lightweight query Transformer to connect two FMs: the giant vision Transformer
EVA-ViT-g and a bilingual LLM trained to align with human intentions (referred
to as ChatGLM-6B). Furthermore, we conduct ablative experiments on the
trainable components of the model to identify the crucial factors for effective
transfer learning. Our findings demonstrate that unfreezing EVA-ViT-g to learn
medical image representations, followed by parameter-efficient training of
ChatGLM-6B to capture the writing styles of medical reports, is essential for
achieving optimal results. Our best attempt (PCLmed Team) achieved the 4th and
the 2nd, respectively, out of 13 participating teams, based on the BERTScore
and ROUGE-1 metrics, in the ImageCLEFmedical Caption 2023 Caption Prediction
Task competition.
