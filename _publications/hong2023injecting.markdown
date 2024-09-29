---
layout: publication
title: 3D45;LLM Injecting The 3D World Into Large Language Models
authors: Hong Yining, Zhen Haoyu, Chen Peihao, Zheng Shuhong, Du Yilun, Chen Zhenfang, Gan Chuang
conference: "Arxiv"
year: 2023
bibkey: hong2023injecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.12981"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) and Vision45;Language Models (VLMs) have been proven to excel at multiple tasks such as commonsense reasoning. Powerful as these models can be they are not grounded in the 3D physical world which involves richer concepts such as spatial relationships affordances physics layout and so on. In this work we propose to inject the 3D world into large language models and introduce a whole new family of 3D45;LLMs. Specifically 3D45;LLMs can take 3D point clouds and their features as input and perform a diverse set of 3D45;related tasks including captioning dense captioning 3D question answering task decomposition 3D grounding 3D45;assisted dialog navigation and so on. Using three types of prompting mechanisms that we design we are able to collect over 300k 3D45;language data covering these tasks. To efficiently train 3D45;LLMs we first utilize a 3D feature extractor that obtains 3D features from rendered multi45; view images. Then we use 2D VLMs as our backbones to train our 3D45;LLMs. By introducing a 3D localization mechanism 3D45;LLMs can better capture 3D spatial information. Experiments on ScanQA show that our model outperforms state45;of45;the45;art baselines by a large margin (e.g. the BLEU45;1 score surpasses state45;of45;the45;art score by 937;). Furthermore experiments on our held45;in datasets for 3D captioning task composition and 3D45;assisted dialogue show that our model outperforms 2D VLMs. Qualitative examples also show that our model could perform more tasks beyond the scope of existing LLMs and VLMs. Project Page https://vis&#45;www.cs.umass.edu/3dllm/.
