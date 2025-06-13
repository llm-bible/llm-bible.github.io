---
layout: publication
title: 'Croc: Pretraining Large Multimodal Models With Cross-modal Comprehension'
authors: Yin Xie, Kaicheng Yang, Ninghua Yang, Weimo Deng, Xiangzi Dai, Tiancheng Gu, Yumeng Wang, Xiang An, Yongle Zhao, Ziyong Feng, Roy Miles, Ismail Elezi, Jiankang Deng
conference: "Arxiv"
year: 2024
bibkey: xie2024pretraining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14332"}
  - {name: "Code", url: "https://github.com/deepglint/Croc"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Transformer', 'Has Code', 'Prompting', 'Attention Mechanism']
---
Recent advances in Large Language Models (LLMs) have catalyzed the
development of Large Multimodal Models (LMMs). However, existing research
primarily focuses on tuning language and image instructions, ignoring the
critical pretraining phase where models learn to process textual and visual
modalities jointly. In this paper, we propose a new pretraining paradigm for
LMMs to enhance the visual comprehension capabilities of LLMs by introducing a
novel cross-modal comprehension stage. Specifically, we design a dynamically
learnable prompt token pool and employ the Hungarian algorithm to replace part
of the original visual tokens with the most relevant prompt tokens. Then, we
conceptualize visual tokens as analogous to a "foreign language" for the LLMs
and propose a mixed attention mechanism with bidirectional visual attention and
unidirectional textual attention to comprehensively enhance the understanding
of visual tokens. Meanwhile, we integrate a detailed caption generation task,
leveraging rich descriptions to further facilitate LLMs in understanding visual
semantic information. After pretraining on 1.5 million publicly accessible
data, we present a new foundation model called Croc. Experimental results
demonstrate that Croc achieves new state-of-the-art performance on massive
vision-language benchmarks. To support reproducibility and facilitate further
research, we release the training code and pre-trained model weights at
https://github.com/deepglint/Croc.
