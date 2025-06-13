---
layout: publication
title: 'Yulan: An Open-source Large Language Model'
authors: Yutao Zhu, Kun Zhou, Kelong Mao, Wentong Chen, Yiding Sun, Zhipeng Chen, Qian Cao, Yihan Wu, Yushuo Chen, Feng Wang, Lei Zhang, Junyi Li, Xiaolei Wang, Lei Wang, Beichen Zhang, Zican Dong, Xiaoxue Cheng, Yuhan Chen, Xinyu Tang, Yupeng Hou, Qiangqiang Ren, Xincheng Pang, Shufang Xie, Wayne Xin Zhao, Zhicheng Dou, Jiaxin Mao, Yankai Lin, Ruihua Song, Jun Xu, Xu Chen, Rui Yan, Zhewei Wei, Di Hu, Wenbing Huang, Ze-feng Gao, Yueguo Chen, Weizheng Lu, Ji-rong Wen
conference: "Arxiv"
year: 2024
bibkey: zhu2024open
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.19853'}
  - {name: "Code", url: 'https://github.com/RUC-GSAI/YuLan-Chat'}
tags: ['Has Code', 'RAG', 'Tools', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Pre-Training']
---
Large language models (LLMs) have become the foundation of many applications,
leveraging their extensive capabilities in processing and understanding natural
language. While many open-source LLMs have been released with technical
reports, the lack of training details hinders further research and development.
This paper presents the development of YuLan, a series of open-source LLMs with
\\(12\\) billion parameters. The base model of YuLan is pre-trained on
approximately \\(1.7\\)T tokens derived from a diverse corpus, including massive
English, Chinese, and multilingual texts. We design a three-stage pre-training
method to enhance YuLan's overall capabilities. Subsequent phases of training
incorporate instruction-tuning and human alignment, employing a substantial
volume of high-quality synthesized data. To facilitate the learning of complex
and long-tail knowledge, we devise a curriculum-learning framework throughout
across these stages, which helps LLMs learn knowledge in an easy-to-hard
manner. YuLan's training is finished on Jan, 2024 and has achieved performance
on par with state-of-the-art LLMs across various English and Chinese
benchmarks. This paper outlines a comprehensive technical roadmap for
developing LLMs from scratch. Our model and codes are available at
https://github.com/RUC-GSAI/YuLan-Chat.
