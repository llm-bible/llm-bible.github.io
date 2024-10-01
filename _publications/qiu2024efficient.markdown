---
layout: publication
title: 'Efficient Interactive LLM Serving With Proxy Model-based Sequence Length Prediction'
authors: Qiu Haoran, Mao Weichao, Patke Archit, Cui Shengkun, Jha Saurabh, Wang Chen, Franke Hubertus, Kalbarczyk Zbigniew T., Başar Tamer, Iyer Ravishankar K.
conference: "Arxiv"
year: 2024
bibkey: qiu2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08509"}
tags: ['Applications', 'GPT', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have been driving a new wave of interactive AI applications across numerous domains. However, efficiently serving LLM inference requests is challenging due to their unpredictable execution times originating from the autoregressive nature of generative models. Existing LLM serving systems exploit first-come-first-serve (FCFS) scheduling, suffering from head-of-line blocking issues. To address the non-deterministic nature of LLMs and enable efficient interactive LLM serving, we present a speculative shortest-job-first (SSJF) scheduler that uses a light proxy model to predict LLM output sequence lengths. Our open-source SSJF implementation does not require changes to memory management or batching strategies. Evaluations on real-world datasets and production workload traces show that SSJF reduces average job completion times by 30.5-39.6&#37; and increases throughput by 2.2-3.6x compared to FCFS schedulers, across no batching, dynamic batching, and continuous batching settings.
