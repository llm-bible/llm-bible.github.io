---
layout: publication
title: 'KOSMOS-2.5: A Multimodal Literate Model'
authors: Tengchao Lv, Yupan Huang, Jingye Chen, Yuzhong Zhao, Yilin Jia, Lei Cui, Shuming Ma, Yaoyao Chang, Shaohan Huang, Wenhui Wang, Li Dong, Weiyao Luo, Shaoxiang Wu, Guoxin Wang, Cha Zhang, Furu Wei
conference: "Arxiv"
year: 2023
bibkey: lv2023kosmos
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.11419"}
  - {name: "Code", url: "https://aka.ms/kosmos25"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Has Code', 'Prompting', 'Pre-Training', 'Applications']
---
The automatic reading of text-intensive images represents a significant
advancement toward achieving Artificial General Intelligence (AGI). In this
paper we present KOSMOS-2.5, a multimodal literate model for machine reading of
text-intensive images. Pre-trained on a large-scale corpus of text-intensive
images, KOSMOS-2.5 excels in two distinct yet complementary transcription
tasks: (1) generating spatially-aware text blocks, where each block of text is
assigned spatial coordinates within the image, and (2) producing structured
text output that captures both style and structure in markdown format. This
unified multimodal literate capability is achieved through a shared
decoder-only autoregressive Transformer architecture and task-specific prompts.
Building on this foundation, we fine-tune KOSMOS-2.5 for document understanding
tasks, resulting in a document understanding generalist named KOSMOS-2.5-CHAT.
Additionally, a large corpus of 357.4 million document pages spanning diverse
domains was curated for pre-training. We evaluate KOSMOS-2.5 on two newly
proposed benchmarks, OCREval and MarkdownEval, for document-level text
recognition and image-to-markdown generation, demonstrating impressive literate
capabilities comparable to GPT-4o. KOSMOS-2.5-CHAT achieves performance
comparable to other state-of-the-art generalists that are five times larger
(1.3B vs. 7B) across nine text-rich visual question answering benchmarks.
Models and code have been available at \url\{https://aka.ms/kosmos25\}.
