---
layout: publication
title: 'Vita-audio: Fast Interleaved Cross-modal Token Generation For Efficient Large Speech-language Model'
authors: Zuwei Long, Yunhang Shen, Chaoyou Fu, Heting Gao, Lijiang Li, Peixian Chen, Mengdan Zhang, Hang Shao, Jian Li, Jinlong Peng, Haoyu Cao, Ke Li, Rongrong Ji, Xing Sun
conference: "Arxiv"
year: 2025
bibkey: long2025vita
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03739"}
tags: ['INTERSPEECH', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
With the growing requirement for natural human-computer interaction,
speech-based systems receive increasing attention as speech is one of the most
common forms of daily communication. However, the existing speech models still
experience high latency when generating the first audio token during streaming,
which poses a significant bottleneck for deployment. To address this issue, we
propose VITA-Audio, an end-to-end large speech model with fast audio-text token
generation. Specifically, we introduce a lightweight Multiple Cross-modal Token
Prediction (MCTP) module that efficiently generates multiple audio tokens
within a single model forward pass, which not only accelerates the inference
but also significantly reduces the latency for generating the first audio in
streaming scenarios. In addition, a four-stage progressive training strategy is
explored to achieve model acceleration with minimal loss of speech quality. To
our knowledge, VITA-Audio is the first multi-modal large language model capable
of generating audio output during the first forward pass, enabling real-time
conversational capabilities with minimal latency. VITA-Audio is fully
reproducible and is trained on open-source data only. Experimental results
demonstrate that our model achieves an inference speedup of 3~5x at the 7B
parameter scale, but also significantly outperforms open-source models of
similar model size on multiple benchmarks for automatic speech recognition
(ASR), text-to-speech (TTS), and spoken question answering (SQA) tasks.
