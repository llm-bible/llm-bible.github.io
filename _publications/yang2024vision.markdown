---
layout: publication
title: Vision Model Pre-training on Interleaved Image-Text Data via Latent Compression Learning
authors: Yang Chenyu, Zhu Xizhou, Zhu Jinguo, Su Weijie, Wang Junjie, Dong Xuan, Wang Wenhai, Lu Lewei, Li Bin, Zhou Jie, Qiao Yu, Dai Jifeng
conference: "Arxiv"
year: 2024
bibkey: yang2024vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07543"}
  - {name: "Code", url: "https://github.com/OpenGVLab/LCL"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recently vision model pre-training has evolved from relying on manually annotated datasets to leveraging large-scale web-crawled image-text data. Despite these advances there is no pre-training method that effectively exploits the interleaved image-text data which is very prevalent on the Internet. Inspired by the recent success of compression learning in natural language processing we propose a novel vision model pre-training method called Latent Compression Learning (LCL) for interleaved image-text data. This method performs latent compression learning by maximizing the mutual information between the inputs and outputs of a causal attention model. The training objective can be decomposed into two basic tasks 1) contrastive learning between visual representation and preceding context and 2) generating subsequent text based on visual representation. Our experiments demonstrate that our method not only matches the performance of CLIP on paired pre-training datasets (e.g. LAION) but can also leverage interleaved pre-training data (e.g. MMC4) to learn robust visual representation from scratch showcasing the potential of vision model pre-training with interleaved image-text data. Code is released at https://github.com/OpenGVLab/LCL.
