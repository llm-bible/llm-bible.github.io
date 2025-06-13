---
layout: publication
title: 'Spark-tts: An Efficient Llm-based Text-to-speech Model With Single-stream Decoupled Speech Tokens'
authors: Xinsheng Wang, Mingqi Jiang, Ziyang Ma, Ziyu Zhang, Songxiang Liu, Linqin Li, Zheng Liang, Qixi Zheng, Rui Wang, Xiaoqin Feng, Weizhen Bian, Zhen Ye, Sitong Cheng, Ruibin Yuan, Zhixian Zhao, Xinfa Zhu, Jiahao Pan, Liumeng Xue, Pengcheng Zhu, Yunlin Chen, Zhifei Li, Xie Chen, Lei Xie, Yike Guo, Wei Xue
conference: "Arxiv"
year: 2025
bibkey: wang2025spark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01710"}
  - {name: "Code", url: "https://github.com/SparkAudio/Spark-TTS"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Has Code']
---
Recent advancements in large language models (LLMs) have driven significant
progress in zero-shot text-to-speech (TTS) synthesis. However, existing
foundation models rely on multi-stage processing or complex architectures for
predicting multiple codebooks, limiting efficiency and integration flexibility.
To overcome these challenges, we introduce Spark-TTS, a novel system powered by
BiCodec, a single-stream speech codec that decomposes speech into two
complementary token types: low-bitrate semantic tokens for linguistic content
and fixed-length global tokens for speaker attributes. This disentangled
representation, combined with the Qwen2.5 LLM and a chain-of-thought (CoT)
generation approach, enables both coarse-grained control (e.g., gender,
speaking style) and fine-grained adjustments (e.g., precise pitch values,
speaking rate). To facilitate research in controllable TTS, we introduce
VoxBox, a meticulously curated 100,000-hour dataset with comprehensive
attribute annotations. Extensive experiments demonstrate that Spark-TTS not
only achieves state-of-the-art zero-shot voice cloning but also generates
highly customizable voices that surpass the limitations of reference-based
synthesis. Source code, pre-trained models, and audio samples are available at
https://github.com/SparkAudio/Spark-TTS.
