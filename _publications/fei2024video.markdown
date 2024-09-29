---
layout: publication
title: Video45;ccam Enhancing Video45;language Understanding With Causal Cross45;attention Masks For Short And Long Videos
authors: Fei Jiajun, Li Dian, Deng Zhidong, Wang Zekun, Liu Gang, Wang Hui
conference: "Arxiv"
year: 2024
bibkey: fei2024video
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14023"}
  - {name: "Code", url: "https://github.com/QQ&#45;MM/Video&#45;CCAM&#125;"}
tags: ['Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Multi45;modal large language models (MLLMs) have demonstrated considerable potential across various downstream tasks that require cross45;domain knowledge. MLLMs capable of processing videos known as Video45;MLLMs have attracted broad interest in video45;language understanding. However videos especially long videos contain more visual tokens than images making them difficult for LLMs to process. Existing works either downsample visual features or extend the LLM context size risking the loss of high45;resolution information or slowing down inference speed. To address these limitations we apply cross45;attention layers in the intermediate projector between the visual encoder and the large language model (LLM). As the naive cross45;attention mechanism is insensitive to temporal order we further introduce causal cross45;attention masks (CCAMs) within the cross45;attention layers. This Video45;MLLM named Video45;CCAM is trained in a straightforward two45;stage fashion feature alignment and visual instruction tuning. We develop several Video45;CCAM models based on LLMs of different sizes (4B 9B and 14B). Video45;CCAM proves to be a robust Video45;MLLM and shows outstanding performance from short videos to long ones. Among standard video benchmarks like MVBench and VideoChatGPT45;QA Video45;CCAM shows outstanding performances (1st/2nd/3rd in MVBench and TGIF45;QA 2nd/3rd/4th in MSVD45;QA MSRVTT45;QA and ActivityNet45;QA). In benchmarks encompassing long videos Video45;CCAM models can be directly adapted to long video understanding and still achieve exceptional scores despite being trained solely with images and 1645;frame videos. Using 96 frames (6× the training number of frames) Video45;CCAM models rank 1st/2nd/3rd in VideoVista and 1st/2nd/4th in MLVU among all open45;source Video45;MLLMs respectively. The code is publicly available in url123;https://github.com/QQ&#45;MM/Video&#45;CCAM&#125;.
