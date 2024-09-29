---
layout: publication
title: Smart45;infinity Fast Large Language Model Training Using Near45;storage Processing On A Real System
authors: Jang Hongsun, Song Jaeyong, Jung Jaewon, Park Jaeyoung, Kim Youngsok, Lee Jinho
conference: "Arxiv"
year: 2024
bibkey: jang2024smart
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.06664"}
tags: ['Ethics And Bias', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
The recent huge advance of Large Language Models (LLMs) is mainly driven by the increase in the number of parameters. This has led to substantial memory capacity requirements necessitating the use of dozens of GPUs just to meet the capacity. One popular solution to this is storage45;offloaded training which uses host memory and storage as an extended memory hierarchy. However this obviously comes at the cost of storage bandwidth bottleneck because storage devices have orders of magnitude lower bandwidth compared to that of GPU device memories. Our work Smart45;Infinity addresses the storage bandwidth bottleneck of storage45;offloaded LLM training using near45;storage processing devices on a real system. The main component of Smart45;Infinity is SmartUpdate which performs parameter updates on custom near45;storage accelerators. We identify that moving parameter updates to the storage side removes most of the storage traffic. In addition we propose an efficient data transfer handler structure to address the system integration issues for Smart45;Infinity. The handler allows overlapping data transfers with fixed memory consumption by reusing the device buffer. Lastly we propose accelerator45;assisted gradient compression/decompression to enhance the scalability of Smart45;Infinity. When scaling to multiple near45;storage processing devices the write traffic on the shared channel becomes the bottleneck. To alleviate this we compress the gradients on the GPU and decompress them on the accelerators. It provides further acceleration from reduced traffic. As a result Smart45;Infinity achieves a significant speedup compared to the baseline. Notably Smart45;Infinity is a ready45;to45;use approach that is fully integrated into PyTorch on a real system. We will open45;source Smart45;Infinity to facilitate its use.
