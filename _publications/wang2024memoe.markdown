---
layout: publication
title: Memoe Enhancing Model Editing With Mixture Of Experts Adaptors
authors: Wang Renzhi, Li Piji
conference: "Arxiv"
year: 2024
bibkey: wang2024memoe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19086"}
tags: ['Model Architecture', 'Pretraining Methods']
---
Model editing aims to efficiently alter the behavior of Large Language Models (LLMs) within a desired scope while ensuring no adverse impact on other inputs. Recent years have witnessed various model editing methods been proposed. However these methods either exhibit poor overall performance or struggle to strike a balance between generalization and locality. We propose MEMoE a model editing adapter utilizing a Mixture of Experts (MoE) architecture with a knowledge anchor routing strategy. MEMoE updates knowledge using a bypass MoE structure keeping the original parameters unchanged to preserve the general ability of LLMs. And the knowledge anchor routing ensures that inputs requiring similar knowledge are routed to the same expert thereby enhancing the generalization of the updated knowledge. Experimental results show the superiority of our approach over both batch editing and sequential batch editing tasks exhibiting exceptional overall performance alongside outstanding balance between generalization and locality. Our code will be available.
