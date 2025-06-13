---
layout: publication
title: 'Supervised Fine-tuning In Turn Improves Visual Foundation Models'
authors: Xiaohu Jiang, Yixiao Ge, Yuying Ge, Dachuan Shi, Chun Yuan, Ying Shan
conference: "Arxiv"
year: 2024
bibkey: jiang2024supervised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10222"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Fine-Tuning']
---
Image-text training like CLIP has dominated the pretraining of vision
foundation models in recent years. Subsequent efforts have been made to
introduce region-level visual learning into CLIP's pretraining but face
scalability challenges due to the lack of large-scale region-level datasets.
Drawing inspiration from supervised fine-tuning (SFT) in natural language
processing such as instruction tuning, we explore the potential of fine-grained
SFT in enhancing the generation of vision foundation models after their
pretraining. Thus a two-stage method ViSFT (Vision SFT) is proposed to unleash
the fine-grained knowledge of vision foundation models. In ViSFT, the vision
foundation model is enhanced by performing visual joint learning on some
in-domain tasks and then tested on out-of-domain benchmarks. With updating
using ViSFT on 8 V100 GPUs in less than 2 days, a vision transformer with over
4.4B parameters shows improvements across various out-of-domain benchmarks
including vision and vision-linguistic scenarios.
