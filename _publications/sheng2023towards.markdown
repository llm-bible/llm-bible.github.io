---
layout: publication
title: 'Towards More Unified In-context Visual Understanding'
authors: Sheng Dianmo, Chen Dongdong, Tan Zhentao, Liu Qiankun, Chu Qi, Bao Jianmin, Gong Tao, Liu Bin, Xu Shengwei, Yu Nenghai
conference: "Arxiv"
year: 2023
bibkey: sheng2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02520"}
tags: ['In Context Learning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Transformer']
---
The rapid advancement of large language models (LLMs) has accelerated the
emergence of in-context learning (ICL) as a cutting-edge approach in the
natural language processing domain. Recently, ICL has been employed in visual
understanding tasks, such as semantic segmentation and image captioning,
yielding promising results. However, existing visual ICL framework can not
enable producing content across multiple modalities, which limits their
potential usage scenarios. To address this issue, we present a new ICL
framework for visual understanding with multi-modal output enabled. First, we
quantize and embed both text and visual prompt into a unified representational
space, structured as interleaved in-context sequences. Then a decoder-only
sparse transformer architecture is employed to perform generative modeling on
them, facilitating in-context learning. Thanks to this design, the model is
capable of handling in-context vision understanding tasks with multimodal
output in a unified pipeline.Experimental results demonstrate that our model
achieves competitive performance compared with specialized models and previous
ICL baselines. Overall, our research takes a further step toward unified
multimodal in-context learning.
