---
layout: publication
title: 'Mora: Enabling Generalist Video Generation Via A Multi-agent Framework'
authors: Zhengqing Yuan, Yixin Liu, Yihan Cao, Weixiang Sun, Haolong Jia, Ruoxi Chen, Zhaoxu Li, Bin Lin, Li Yuan, Lifang He, Chi Wang, Yanfang Ye, Lichao Sun
conference: "Arxiv"
year: 2024
bibkey: yuan2024enabling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.13248'}
  - {name: "Code", url: 'https://github.com/lichao-sun/Mora'}
tags: ['Agentic', 'Has Code', 'Agent', 'RAG', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Text-to-video generation has made significant strides, but replicating the
capabilities of advanced systems like OpenAI Sora remains challenging due to
their closed-source nature. Existing open-source methods struggle to achieve
comparable performance, often hindered by ineffective agent collaboration and
inadequate training data quality. In this paper, we introduce Mora, a novel
multi-agent framework that leverages existing open-source modules to replicate
Sora functionalities. We address these fundamental limitations by proposing
three key techniques: (1) multi-agent fine-tuning with a self-modulation factor
to enhance inter-agent coordination, (2) a data-free training strategy that
uses large models to synthesize training data, and (3) a human-in-the-loop
mechanism combined with multimodal large language models for data filtering to
ensure high-quality training datasets. Our comprehensive experiments on six
video generation tasks demonstrate that Mora achieves performance comparable to
Sora on VBench, outperforming existing open-source methods across various
tasks. Specifically, in the text-to-video generation task, Mora achieved a
Video Quality score of 0.800, surpassing Sora 0.797 and outperforming all other
baseline models across six key metrics. Additionally, in the image-to-video
generation task, Mora achieved a perfect Dynamic Degree score of 1.00,
demonstrating exceptional capability in enhancing motion realism and achieving
higher Imaging Quality than Sora. These results highlight the potential of
collaborative multi-agent systems and human-in-the-loop mechanisms in advancing
text-to-video generation. Our code is available at
\url\{https://github.com/lichao-sun/Mora\}.
