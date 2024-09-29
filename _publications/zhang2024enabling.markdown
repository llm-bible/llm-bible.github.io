---
layout: publication
title: Longcite Enabling Llms To Generate Fine45;grained Citations In Long45;context QA
authors: Zhang Jiajie, Bai Yushi, Lv Xin, Gu Wanjun, Liu Danqing, Zou Minhao, Cao Shulin, Hou Lei, Dong Yuxiao, Feng Ling, Li Juanzi
conference: "Arxiv"
year: 2024
bibkey: zhang2024enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02897"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'RAG']
---
Though current long45;context large language models (LLMs) have demonstrated impressive capacities in answering user questions based on extensive text the lack of citations in their responses makes user verification difficult leading to concerns about their trustworthiness due to their potential hallucinations. In this work we aim to enable long45;context LLMs to generate responses with fine45;grained sentence45;level citations improving their faithfulness and verifiability. We first introduce LongBench45;Cite an automated benchmark for assessing current LLMs performance in Long45;Context Question Answering with Citations (LQAC) revealing considerable room for improvement. To this end we propose CoF (Coarse to Fine) a novel pipeline that utilizes off45;the45;shelf LLMs to automatically generate long45;context QA instances with precise sentence45;level citations and leverage this pipeline to construct LongCite45;45k a large45;scale SFT dataset for LQAC. Finally we train LongCite45;8B and LongCite45;9B using the LongCite45;45k dataset successfully enabling their generation of accurate responses and fine45;grained sentence45;level citations in a single output. The evaluation results on LongBench45;Cite show that our trained models achieve state45;of45;the45;art citation quality surpassing advanced proprietary models including GPT45;4o.
