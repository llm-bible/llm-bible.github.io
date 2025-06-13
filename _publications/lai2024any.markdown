---
layout: publication
title: 'Spider: Any-to-many Multimodal LLM'
authors: Jinxiang Lai, Jie Zhang, Jun Liu, Jian Li, Xiaocheng Lu, Song Guo
conference: "Arxiv"
year: 2024
bibkey: lai2024any
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.09439"}
  - {name: "Code", url: "https://github.com/Layjins/Spider"}
tags: ['Tools', 'Reinforcement Learning', 'Has Code', 'Multimodal Models', 'Prompting']
---
Multimodal LLMs (MLLMs) have emerged as an extension of Large Language Models
(LLMs), enabling the integration of various modalities. However, Any-to-Any
MLLMs are limited to generating pairwise modalities 'Text + X' within a single
response, such as Text + \{Image or Audio or Video\}. To address this limitation,
we introduce Spider, a novel efficient Any-to-Many Modalities Generation (AMMG)
framework, which can generate an arbitrary combination of modalities 'Text +
Xs', such as Text + \{Image and Audio and Video\}. To achieve efficient AMMG, our
Spider integrates three core components: a Base Model for basic X-to-X (i.e.,
Any-to-Any) modality processing, an Any-to-Many Instruction Template designed
for producing Xs signal prompts, and a novel Efficient Decoders-Controller for
controlling multimodal Decoders to generate Xs (many-modal) contents. To train
Spider, we constructed a novel Text-formatted Many-Modal (TMM) dataset, which
facilitates learning the X-to-Xs (i.e., Any-to-Many) capability necessary for
AMMG. Ultimately, the well-trained Spider generates a pseudo X-to-Xs dataset,
the first-ever X-to-Xs many-modal dataset, enhancing the potential for AMMG
tasks in future research. Overall, this work not only pushes the boundary of
multimodal interaction but also provides rich data support for advancing the
field. Code: https://github.com/Layjins/Spider
