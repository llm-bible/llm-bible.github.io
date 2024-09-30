---
layout: publication
title: 'Enabling Multimodal Generation On CLIP Via Vision-language Knowledge Distillation'
authors: Dai Wenliang, Hou Lu, Shang Lifeng, Jiang Xin, Liu Qun, Fung Pascale
conference: "Arxiv"
year: 2022
bibkey: dai2022enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.06386"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Multimodal Models', 'Training Techniques']
---
The recent large-scale vision-language pre-training (VLP) of dual-stream architectures (e.g. CLIP) with a tremendous amount of image-text pair data has shown its superiority on various multimodal alignment tasks. Despite its success the resulting models are not capable of multimodal generative tasks due to the weak text encoder. To tackle this problem we propose to augment the dual-stream VLP model with a textual pre-trained language model (PLM) via vision-language knowledge distillation (VLKD) enabling the capability for multimodal generation. VLKD is pretty data- and computation-efficient compared to the pre-training from scratch. Experimental results show that the resulting model has strong zero-shot performance on multimodal generation tasks such as open-ended visual question answering and image captioning. For example it achieves 44.537; zero-shot accuracy on the VQAv2 dataset surpassing the previous state-of-the-art zero-shot model with (7times) fewer parameters. Furthermore the original textual language understanding and generation ability of the PLM is maintained after VLKD which makes our model versatile for both multimodal and unimodal tasks.
