---
layout: publication
title: Empowering 1000 Tokens/second On45;device LLM Prefilling With Mllm45;npu
authors: Xu Daliang, Zhang Hao, Yang Liming, Liu Ruiqi, Huang Gang, Xu Mengwei, Liu Xuanzhe
conference: "Arxiv"
year: 2024
bibkey: xu2024empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05858"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Transformer']
---
On45;device large language models (LLMs) are catalyzing novel mobile applications such as UI task automation and personalized email auto45;reply without giving away users private data. However on45;device LLMs still suffer from unacceptably long inference latency especially the time to first token (prefill stage) due to the need of long context for accurate personalized content generation as well as the lack of parallel computing capacity of mobile CPU/GPU. To enable practical on45;device LLM we present mllm45;NPU the first45;of45;its45;kind LLM inference system that efficiently leverages on45;device Neural Processing Unit (NPU) offloading. Essentially mllm45;NPU is an algorithm45;system co45;design that tackles a few semantic gaps between the LLM architecture and contemporary NPU design. Specifically it re45;constructs the prompt and model in three levels (1) At prompt level it divides variable45;length prompts into multiple fixed45;sized chunks while maintaining data dependencies; (2) At tensor level it identifies and extracts significant outliers to run on the CPU/GPU in parallel with minimal overhead; (3) At block level it schedules Transformer blocks in an out45;of45;order manner to the CPU/GPU and NPU based on their hardware affinity and sensitivity to accuracy. Compared to competitive baselines mllm45;NPU achieves 22.4x faster prefill speed and 30.7x energy savings on average and up to 32.8x speedup in an end45;to45;end real45;world application. For the first time mllm45;NPU achieves more than 1000 tokens/sec prefilling for a billion45;sized model (Qwen1.545;1.8B) paving the way towards practical on45;device LLM.
