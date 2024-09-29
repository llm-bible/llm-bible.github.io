---
layout: publication
title: SLO-aware GPU Frequency Scaling for Energy Efficient LLM Inference Serving
authors: Kakolyris Andreas Kosmas, Masouros Dimosthenis, Vavaroutsos Petros, Xydis Sotirios, Soudris Dimitrios
conference: "Arxiv"
year: 2024
bibkey: kakolyris2024slo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05235"}
tags: ['Efficiency And Optimization', 'RAG', 'Tools']
---
As Large Language Models (LLMs) gain traction their reliance on power-hungry GPUs places ever-increasing energy demands raising environmental and monetary concerns. Inference dominates LLM workloads presenting a critical challenge for providers minimizing energy costs under Service-Level Objectives (SLOs) that ensure optimal user experience. In this paper we present a framework that reduces energy consumption while meeting SLOs through the use of instance and GPU frequency scaling. features mechanisms that project future KV cache usage and batch size. Leveraging a Machine-Learning (ML) model that receives these projections as inputs manages performance at the iteration level to satisfy SLOs with reduced frequencies and instance sizes. We show that the proposed ML model achieves R^2 scores greater than 0.97 and miss-predicts performance by less than 1 iteration per second on average. Experimental results on LLM inference traces show that achieves up to 43.8 lower energy consumption and an energy efficiency improvement of at least 1.71× under SLOs when compared to NVIDIAs Triton server.
