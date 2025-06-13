---
layout: publication
title: 'Funaudiollm: Voice Understanding And Generation Foundation Models For Natural Interaction Between Humans And Llms'
authors: Keyu An, Qian Chen, Chong Deng, Zhihao Du, Changfeng Gao, Zhifu Gao, Yue Gu, Ting He, Hangrui Hu, Kai Hu, Shengpeng Ji, Yabin Li, Zerui Li, Heng Lu, Haoneng Luo, Xiang Lv, Bin Ma, Ziyang Ma, Chongjia Ni, Changhe Song, Jiaqi Shi, Xian Shi, Hao Wang, Wen Wang, Yuxuan Wang, Zhangyu Xiao, Zhijie Yan, Yexin Yang, Bin Zhang, Qinglin Zhang, Shiliang Zhang, Nan Zhao, Siqi Zheng
conference: "Arxiv"
year: 2024
bibkey: an2024voice
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04051"}
  - {name: "Code", url: "https://fun-audio-llm.github.io,"}
  - {name: "Code", url: "https://github.com/FunAudioLLM"}
tags: ['Fine-Tuning', 'INTERSPEECH', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
This report introduces FunAudioLLM, a model family designed to enhance
natural voice interactions between humans and large language models (LLMs). At
its core are two innovative models: SenseVoice, which handles multilingual
speech recognition, emotion recognition, and audio event detection; and
CosyVoice, which facilitates natural speech generation with control over
multiple languages, timbre, speaking style, and speaker identity.
SenseVoice-Small delivers exceptionally low-latency ASR for 5 languages, and
SenseVoice-Large supports high-precision ASR for over 50 languages, while
CosyVoice excels in multi-lingual voice generation, zero-shot in-context
learning, cross-lingual voice cloning, and instruction-following capabilities.
The models related to SenseVoice and CosyVoice have been open-sourced on
Modelscope and Huggingface, along with the corresponding training, inference,
and fine-tuning codes released on GitHub. By integrating these models with
LLMs, FunAudioLLM enables applications such as speech-to-speech translation,
emotional voice chat, interactive podcasts, and expressive audiobook narration,
thereby pushing the boundaries of voice interaction technology. Demos are
available at https://fun-audio-llm.github.io, and the code can be accessed at
https://github.com/FunAudioLLM.
