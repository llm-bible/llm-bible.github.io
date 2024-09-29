---
layout: publication
title: "Retrieving-to-answer: Zero-shot Video Question Answering With Frozen Large Language Models"
authors: Pan Junting, Lin Ziyi, Ge Yuying, Zhu Xiatian, Zhang Renrui, Wang Yi, Qiao Yu, Li Hongsheng
conference: "Arxiv"
year: 2023
bibkey: pan2023retrieving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.11732"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Video Question Answering (VideoQA) has been significantly advanced from the scaling of recent Large Language Models (LLMs). The key idea is to convert the visual information into the language feature space so that the capacity of LLMs can be fully exploited. Existing VideoQA methods typically take two paradigms (1) learning cross-modal alignment and (2) using an off-the-shelf captioning model to describe the visual data. However the first design needs costly training on many extra multi-modal data whilst the second is further limited by limited domain generalization. To address these limitations a simple yet effective Retrieving-to-Answer (R2A) framework is proposed.Given an input video R2A first retrieves a set of semantically similar texts from a generic text corpus using a pre-trained multi-modal model (e.g. CLIP). With both the question and the retrieved texts a LLM (e.g. DeBERTa) can be directly used to yield a desired answer. Without the need for cross-modal fine-tuning R2A allows for all the key components (e.g. LLM retrieval model and text corpus) to plug-and-play. Extensive experiments on several VideoQA benchmarks show that despite with 1.3B parameters and no fine-tuning our R2A can outperform the 61 times larger Flamingo-80B model even additionally trained on nearly 2.1B multi-modal data.
