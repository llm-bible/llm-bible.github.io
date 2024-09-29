---
layout: publication
title: Deepspeed45;fastgen High45;throughput Text Generation For Llms Via MII And Deepspeed45;inference
authors: Holmes Connor, Tanaka Masahiro, Wyatt Michael, Awan Ammar Ahmad, Rasley Jeff, Rajbhandari Samyam, Aminabadi Reza Yazdani, Qin Heyang, Bakhtiari Arash, Kurilenko Lev, He Yuxiong
conference: "Arxiv"
year: 2024
bibkey: holmes2024deepspeed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08671"}
tags: ['Applications', 'Fine Tuning', 'Language Modeling', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
The deployment and scaling of large language models (LLMs) have become critical as they permeate various applications demanding high45;throughput and low45;latency serving systems. Existing frameworks struggle to balance these requirements especially for workloads with long prompts. This paper introduces DeepSpeed45;FastGen a system that employs Dynamic SplitFuse a novel prompt and generation composition strategy to deliver up to 2.3x higher effective throughput 2x lower latency on average and up to 3.7x lower (token45;level) tail latency compared to state45;of45;the45;art systems like vLLM. We leverage a synergistic combination of DeepSpeed45;MII and DeepSpeed45;Inference to provide an efficient and easy45;to45;use serving system for LLMs. DeepSpeed45;FastGens advanced implementation supports a range of models and offers both non45;persistent and persistent deployment options catering to diverse user scenarios from interactive sessions to long45;running applications. We present a detailed benchmarking methodology analyze the performance through latency45;throughput curves and investigate scalability via load balancing. Our evaluations demonstrate substantial improvements in throughput and latency across various models and hardware configurations. We discuss our roadmap for future enhancements including broader model support and new hardware backends. The DeepSpeed45;FastGen code is readily available for community engagement and contribution.
