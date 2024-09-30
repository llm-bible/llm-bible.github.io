---
layout: publication
title: 'Yulan: An Open-source Large Language Model'
authors: Zhu Yutao, Zhou Kun, Mao Kelong, Chen Wentong, Sun Yiding, Chen Zhipeng, Cao Qian, Wu Yihan, Chen Yushuo, Wang Feng, Zhang Lei, Li Junyi, Wang Xiaolei, Wang Lei, Zhang Beichen, Dong Zican, Cheng Xiaoxue, Chen Yuhan, Tang Xinyu, Hou Yupeng, Ren Qiangqiang, Pang Xincheng, Xie Shufang, Zhao Wayne Xin, Dou Zhicheng, Mao Jiaxin, Lin Yankai, Song Ruihua, Xu Jun, Chen Xu, Yan Rui, Wei Zhewei, Hu Di, Huang Wenbing, Gao Ze-feng, Chen Yueguo, Lu Weizheng, Wen Ji-rong
conference: "Arxiv"
year: 2024
bibkey: zhu2024open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19853"}
  - {name: "Code", url: "https://github.com/RUC-GSAI/YuLan-Chat"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have become the foundation of many applications leveraging their extensive capabilities in processing and understanding natural language. While many open-source LLMs have been released with technical reports the lack of training details hinders further research and development. This paper presents the development of YuLan a series of open-source LLMs with (12) billion parameters. The base model of YuLan is pre-trained on approximately (1.7)T tokens derived from a diverse corpus including massive English Chinese and multilingual texts. We design a three-stage pre-training method to enhance YuLans overall capabilities. Subsequent phases of training incorporate instruction-tuning and human alignment employing a substantial volume of high-quality synthesized data. To facilitate the learning of complex and long-tail knowledge we devise a curriculum-learning framework throughout across these stages which helps LLMs learn knowledge in an easy-to-hard manner. YuLans training is finished on Jan 2024 and has achieved performance on par with state-of-the-art LLMs across various English and Chinese benchmarks. This paper outlines a comprehensive technical roadmap for developing LLMs from scratch. Our model and codes are available at https://github.com/RUC-GSAI/YuLan-Chat."
