---
layout: publication
title: 'Youku-mplug: A 10 Million Large-scale Chinese Video-language Dataset For Pre-training And Benchmarks'
authors: Haiyang Xu, Qinghao Ye, Xuan Wu, Ming Yan, Yuan Miao, Jiabo Ye, Guohai Xu, Anwen Hu, Yaya Shi, Guangwei Xu, Chenliang Li, Qi Qian, Maofei Que, Ji Zhang, Xiao Zeng, Fei Huang
conference: "Arxiv"
year: 2023
bibkey: xu2023youku
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.04362"}
tags: ['Responsible AI', 'Pre-Training', 'Applications', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
To promote the development of Vision-Language Pre-training (VLP) and
multimodal Large Language Model (LLM) in the Chinese community, we firstly
release the largest public Chinese high-quality video-language dataset named
Youku-mPLUG, which is collected from Youku, a well-known Chinese video-sharing
website, with strict criteria of safety, diversity, and quality. Youku-mPLUG
contains 10 million Chinese video-text pairs filtered from 400 million raw
videos across a wide range of 45 diverse categories for large-scale
pre-training. In addition, to facilitate a comprehensive evaluation of
video-language models, we carefully build the largest human-annotated Chinese
benchmarks covering three popular video-language tasks of cross-modal
retrieval, video captioning, and video category classification. Youku-mPLUG can
enable researchers to conduct more in-depth multimodal research and develop
better applications in the future. Furthermore, we release popular
video-language pre-training models, ALPRO and mPLUG-2, and our proposed
modularized decoder-only model mPLUG-video pre-trained on Youku-mPLUG.
Experiments show that models pre-trained on Youku-mPLUG gain up to 23.1%
improvement in video category classification. Besides, mPLUG-video achieves a
new state-of-the-art result on these benchmarks with 80.5% top-1 accuracy in
video category classification and 68.9 CIDEr score in video captioning,
respectively. Finally, we scale up mPLUG-video based on the frozen Bloomz with
only 1.7% trainable parameters as Chinese multimodal LLM, and demonstrate
impressive instruction and video understanding ability. The zero-shot
instruction understanding experiment indicates that pretraining with
Youku-mPLUG can enhance the ability to comprehend overall and detailed visual
semantics, recognize scene text, and leverage open-domain knowledge.
