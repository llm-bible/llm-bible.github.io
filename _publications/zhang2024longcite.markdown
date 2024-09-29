---
layout: publication
title: Longcite Enabling Llms To Generate Fine-grained Citations In Long-context QA
authors: Zhang Jiajie, Bai Yushi, Lv Xin, Gu Wanjun, Liu Danqing, Zou Minhao, Cao Shulin, Hou Lei, Dong Yuxiao, Feng Ling, Li Juanzi
conference: "Arxiv"
year: 2024
bibkey: zhang2024longcite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02897"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'RAG']
---
Though current long-context large language models (LLMs) have demonstrated impressive capacities in answering user questions based on extensive text the lack of citations in their responses makes user verification difficult leading to concerns about their trustworthiness due to their potential hallucinations. In this work we aim to enable long-context LLMs to generate responses with fine-grained sentence-level citations improving their faithfulness and verifiability. We first introduce LongBench-Cite an automated benchmark for assessing current LLMs performance in Long-Context Question Answering with Citations (LQAC) revealing considerable room for improvement. To this end we propose CoF (Coarse to Fine) a novel pipeline that utilizes off-the-shelf LLMs to automatically generate long-context QA instances with precise sentence-level citations and leverage this pipeline to construct LongCite-45k a large-scale SFT dataset for LQAC. Finally we train LongCite-8B and LongCite-9B using the LongCite-45k dataset successfully enabling their generation of accurate responses and fine-grained sentence-level citations in a single output. The evaluation results on LongBench-Cite show that our trained models achieve state-of-the-art citation quality surpassing advanced proprietary models including GPT-4o.
