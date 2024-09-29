---
layout: publication
title: Amphista Accelerate LLM Inference With Bi45;directional Multiple Drafting Heads In A Non45;autoregressive Style
authors: Li Zeping, Yang Xinlong, Gao Ziheng, Liu Ji, Liu Zhuang, Li Dong, Peng Jinzhang, Tian Lu, Barsoum Emad
conference: "Arxiv"
year: 2024
bibkey: li2024accelerate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13170"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Merging', 'Model Architecture', 'Pretraining Methods']
---
Large Language Models (LLMs) inherently use autoregressive decoding which lacks parallelism in inference and results in significantly slow inference speeds especially when hardware parallel accelerators and memory bandwidth are not fully utilized. In this work we propose Amphista a speculative decoding algorithm that adheres to a non45;autoregressive decoding paradigm. Owing to the increased parallelism our method demonstrates higher efficiency in inference compared to autoregressive methods. Specifically Amphista models an Auto45;embedding Block capable of parallel inference incorporating bi45;directional attention to enable interaction between different drafting heads. Additionally Amphista implements Staged Adaptation Layers to facilitate the transition of semantic information from the base models autoregressive inference to the drafting heads non45;autoregressive speculation thereby achieving paradigm transformation and feature fusion. We conduct a series of experiments on a suite of Vicuna models using MT45;Bench and Spec45;Bench. For the Vicuna 33B model Amphista achieves up to 2.75× and 1.40× wall45;clock acceleration compared to vanilla autoregressive decoding and Medusa respectively while preserving lossless generation quality.
