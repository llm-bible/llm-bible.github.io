---
layout: publication
title: 'Imagebind-llm: Multi-modality Instruction Tuning'
authors: Jiaming Han, Renrui Zhang, Wenqi Shao, Peng Gao, Peng Xu, Han Xiao, Kaipeng Zhang, Chris Liu, Song Wen, Ziyu Guo, Xudong Lu, Shuai Ren, Yafei Wen, Xiaoxin Chen, Xiangyu Yue, Hongsheng Li, Yu Qiao
conference: "Arxiv"
year: 2023
bibkey: han2023imagebind
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03905"}
  - {name: "Code", url: "https://github.com/OpenGVLab/LLaMA-Adapter"}
tags: ['Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Multimodal Models']
---
We present ImageBind-LLM, a multi-modality instruction tuning method of large
language models (LLMs) via ImageBind. Existing works mainly focus on language
and image instruction tuning, different from which, our ImageBind-LLM can
respond to multi-modality conditions, including audio, 3D point clouds, video,
and their embedding-space arithmetic by only image-text alignment training.
During training, we adopt a learnable bind network to align the embedding space
between LLaMA and ImageBind's image encoder. Then, the image features
transformed by the bind network are added to word tokens of all layers in
LLaMA, which progressively injects visual instructions via an attention-free
and zero-initialized gating mechanism. Aided by the joint embedding of
ImageBind, the simple image-text training enables our model to exhibit superior
multi-modality instruction-following capabilities. During inference, the
multi-modality inputs are fed into the corresponding ImageBind encoders, and
processed by a proposed visual cache model for further cross-modal embedding
enhancement. The training-free cache model retrieves from three million image
features extracted by ImageBind, which effectively mitigates the
training-inference modality discrepancy. Notably, with our approach,
ImageBind-LLM can respond to instructions of diverse modalities and demonstrate
significant language generation quality. Code is released at
https://github.com/OpenGVLab/LLaMA-Adapter.
