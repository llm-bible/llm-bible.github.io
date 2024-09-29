---
layout: publication
title: Fiddler CPU45;GPU Orchestration For Fast Inference Of Mixture45;of45;experts Models
authors: Kamahori Keisuke, Gu Yile, Zhu Kan, Kasikci Baris
conference: "Arxiv"
year: 2024
bibkey: kamahori2024cpu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07033"}
  - {name: "Code", url: "https://github.com/efeslab/fiddler&#125;"}
tags: ['Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) based on Mixture45;of45;Experts (MoE) architecture are showing promising performance on various tasks. However running them on resource45;constrained settings where GPU memory resources are not abundant is challenging due to huge model sizes. Existing systems that offload model weights to CPU memory suffer from the significant overhead of frequently moving data between CPU and GPU. In this paper we propose Fiddler a resource45;efficient inference engine with CPU45;GPU orchestration for MoE models. The key idea of Fiddler is to use the computation ability of the CPU to minimize the data movement between the CPU and GPU. Our evaluation shows that Fiddler can run the uncompressed Mixtral45;8x7B model which exceeds 90GB in parameters to generate over 3 tokens per second on a single GPU with 24GB memory showing an order of magnitude improvement over existing methods. The code of Fiddler is publicly available at url123;https://github.com/efeslab/fiddler&#125;
