---
layout: publication
title: 'Videopoet: A Large Language Model For Zero-shot Video Generation'
authors: Dan Kondratyuk, Lijun Yu, Xiuye Gu, José Lezama, Jonathan Huang, Grant Schindler, Rachel Hornung, Vighnesh Birodkar, Jimmy Yan, Ming-chang Chiu, Krishna Somandepalli, Hassan Akbari, Yair Alon, Yong Cheng, Josh Dillon, Agrim Gupta, Meera Hahn, Anja Hauth, David Hendon, Alonso Martinez, David Minnen, Mikhail Sirotenko, Kihyuk Sohn, Xuan Yang, Hartwig Adam, Ming-hsuan Yang, Irfan Essa, Huisheng Wang, David A. Ross, Bryan Seybold, Lu Jiang
conference: "Arxiv"
year: 2023
bibkey: kondratyuk2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.14125"}
  - {name: "Code", url: "http://sites.research.google/videopoet/"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Pretraining Methods', 'Transformer', 'Has Code']
---
We present VideoPoet, a language model capable of synthesizing high-quality
video, with matching audio, from a large variety of conditioning signals.
VideoPoet employs a decoder-only transformer architecture that processes
multimodal inputs -- including images, videos, text, and audio. The training
protocol follows that of Large Language Models (LLMs), consisting of two
stages: pretraining and task-specific adaptation. During pretraining, VideoPoet
incorporates a mixture of multimodal generative objectives within an
autoregressive Transformer framework. The pretrained LLM serves as a foundation
that can be adapted for a range of video generation tasks. We present empirical
results demonstrating the model's state-of-the-art capabilities in zero-shot
video generation, specifically highlighting VideoPoet's ability to generate
high-fidelity motions. Project page: http://sites.research.google/videopoet/
