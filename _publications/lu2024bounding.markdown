---
layout: publication
title: A Bounding Box Is Worth One Token: Interleaving Layout And Text In A Large Language Model For Document Understanding
authors: Lu Jinghui, Yu Haiyang, Wang Yanjie, Ye Yongjie, Tang Jingqun, Yang Ziwei, Wu Binghong, Liu Qi, Feng Hao, Wang Han, Liu Hao, Huang Can
conference: "Arxiv"
year: 2024
bibkey: lu2024bounding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01976"}
tags: ['Applications', 'GPT', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Recently many studies have demonstrated that exclusively incorporating OCR-derived text and spatial layouts with large language models (LLMs) can be highly effective for document understanding tasks. However existing methods that integrate spatial layouts with text have limitations such as producing overly long text sequences or failing to fully leverage the autoregressive traits of LLMs. In this work we introduce Interleaving Layout and Text in a Large Language Model (LayTextLLM) for document understanding. In particular LayTextLLM projects each bounding box to a single embedding and interleaves it with text efficiently avoiding long sequence issues while leveraging autoregressive traits of LLMs. LayTextLLM not only streamlines the interaction of layout and textual data but also shows enhanced performance in Key Information Extraction (KIE) and Visual Question Answering (VQA). Comprehensive benchmark evaluations reveal significant improvements with a 27.237; increase on KIE tasks and 12.037; on VQA tasks compared to previous state-of-the-art document understanding MLLMs as well as a 15.137; improvement over other SOTA OCR-based LLMs on KIE tasks.
