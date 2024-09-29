---
layout: publication
title: Efficient Interactive LLM Serving With Proxy Model45;based Sequence Length Prediction
authors: Qiu Haoran, Mao Weichao, Patke Archit, Cui Shengkun, Jha Saurabh, Wang Chen, Franke Hubertus, Kalbarczyk Zbigniew T., Başar Tamer, Iyer Ravishankar K.
conference: "Arxiv"
year: 2024
bibkey: qiu2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08509"}
tags: ['Applications', 'GPT', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have been driving a new wave of interactive AI applications across numerous domains. However efficiently serving LLM inference requests is challenging due to their unpredictable execution times originating from the autoregressive nature of generative models. Existing LLM serving systems exploit first45;come45;first45;serve (FCFS) scheduling suffering from head45;of45;line blocking issues. To address the non45;deterministic nature of LLMs and enable efficient interactive LLM serving we present a speculative shortest45;job45;first (SSJF) scheduler that uses a light proxy model to predict LLM output sequence lengths. Our open45;source SSJF implementation does not require changes to memory management or batching strategies. Evaluations on real45;world datasets and production workload traces show that SSJF reduces average job completion times by 30.545;39.637; and increases throughput by 2.245;3.6x compared to FCFS schedulers across no batching dynamic batching and continuous batching settings.
