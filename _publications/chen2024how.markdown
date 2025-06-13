---
layout: publication
title: 'How Far Are We To GPT-4V? Closing The Gap To Commercial Multimodal Models With Open-source Suites'
authors: Zhe Chen, Weiyun Wang, Hao Tian, Shenglong Ye, Zhangwei Gao, Erfei Cui, Wenwen Tong, Kongzhi Hu, Jiapeng Luo, Zheng Ma, Ji Ma, Jiaqi Wang, Xiaoyi Dong, Hang Yan, Hewei Guo, Conghui He, Botian Shi, Zhenjiang Jin, Chao Xu, Bin Wang, Xingjian Wei, Wei Li, Wenjian Zhang, Bo Zhang, Pinlong Cai, Licheng Wen, Xiangchao Yan, Min Dou, Lewei Lu, Xizhou Zhu, Tong Lu, Dahua Lin, Yu Qiao, Jifeng Dai, Wenhai Wang
conference: "Arxiv"
year: 2024
bibkey: chen2024how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.16821'}
  - {name: "Code", url: 'https://github.com/OpenGVLab/InternVL'}
tags: ['Has Code', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
In this report, we introduce InternVL 1.5, an open-source multimodal large
language model (MLLM) to bridge the capability gap between open-source and
proprietary commercial models in multimodal understanding. We introduce three
simple improvements: (1) Strong Vision Encoder: we explored a continuous
learning strategy for the large-scale vision foundation model -- InternViT-6B,
boosting its visual understanding capabilities, and making it can be
transferred and reused in different LLMs. (2) Dynamic High-Resolution: we
divide images into tiles ranging from 1 to 40 of 448\\(\times\\)448 pixels
according to the aspect ratio and resolution of the input images, which
supports up to 4K resolution input. (3) High-Quality Bilingual Dataset: we
carefully collected a high-quality bilingual dataset that covers common scenes,
document images, and annotated them with English and Chinese question-answer
pairs, significantly enhancing performance in OCR- and Chinese-related tasks.
We evaluate InternVL 1.5 through a series of benchmarks and comparative
studies. Compared to both open-source and proprietary models, InternVL 1.5
shows competitive performance, achieving state-of-the-art results in 8 of 18
benchmarks. Code has been released at https://github.com/OpenGVLab/InternVL.
