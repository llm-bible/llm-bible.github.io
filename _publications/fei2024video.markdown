---
layout: publication
title: Video-CCAM Enhancing Video-Language Understanding with Causal Cross-Attention Masks for Short and Long Videos
authors: Fei Jiajun, Li Dian, Deng Zhidong, Wang Zekun, Liu Gang, Wang Hui
conference: "Arxiv"
year: 2024
bibkey: fei2024video
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14023"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Training Techniques', 'Transformer']
---
Multi-modal large language models (MLLMs) have demonstrated considerable potential across various downstream tasks that require cross-domain knowledge. MLLMs capable of processing videos known as Video-MLLMs have attracted broad interest in video-language understanding. However videos especially long videos contain more visual tokens than images making them difficult for LLMs to process. Existing works either downsample visual features or extend the LLM context size risking the loss of high-resolution information or slowing down inference speed. To address these limitations we apply cross-attention layers in the intermediate projector between the visual encoder and the large language model (LLM). As the naive cross-attention mechanism is insensitive to temporal order we further introduce causal cross-attention masks (CCAMs) within the cross-attention layers. This Video-MLLM named Video-CCAM is trained in a straightforward two-stage fashion feature alignment and visual instruction tuning. We develop several Video-CCAM models based on LLMs of different sizes (4B 9B and 14B). Video-CCAM proves to be a robust Video-MLLM and shows outstanding performance from short videos to long ones. Among standard video benchmarks like MVBench and VideoChatGPT-QA Video-CCAM shows outstanding performances (1st/2nd/3rd in MVBench and TGIF-QA 2nd/3rd/4th in MSVD-QA MSRVTT-QA and ActivityNet-QA). In benchmarks encompassing long videos Video-CCAM models can be directly adapted to long video understanding and still achieve exceptional scores despite being trained solely with images and 16-frame videos. Using 96 frames (6times the training number of frames) Video-CCAM models rank 1st/2nd/3rd in VideoVista and 1st/2nd/4th in MLVU among all open-source Video-MLLMs respectively. The code is publicly available in .
