---
layout: publication
title: The Uniqueness Of Llama345;70b With Per45;channel Quantization An Empirical Study
authors: Qin Minghai
conference: "Arxiv"
year: 2024
bibkey: qin2024uniqueness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15301"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Transformer']
---
We have observed a distinctive quantization45;related behavior in the LLaMA3/3.145;70B models that is absent in both the LLaMA245;70B and LLaMA3/3.145;8B/405B models. Quantization is a crucial technique for deploying large language models (LLMs) efficiently. Among various bit widths and representations for weights and activations the 845;bit integer weight and 845;bit integer activation (W8A8) configuration is particularly popular due to its widespread hardware support. However the impact of W8A8 post45;training quantization on model accuracy remains contentious. While several studies have suggested calibrating either weights or activations to mitigate accuracy degradation a comprehensive solution has yet to be identified. In this paper we empirically investigate multiple LLMs featured on an open LLM leaderboard discovering that the LLaMA345;70B model series have a unique accuracy degradation behavior with W8A8 per45;channel post45;training quantization. In contrast other model series such as LLaMA2 LLaMA345;8B Qwen Mixtral Mistral Phi45;3 and Falcon demonstrate robust performance with W8A8 sometimes surpassing their FP16 counterparts. Contrary to previous assertions attributing degradation to the large dynamic range of activations our findings indicate that the weight distribution of the LLaMA345;70B is the primary factor behind the vulnerability. By meticulously analyzing the distinct characteristics of weight distributions across Transformer blocks we propose a mixed strategy with less than 337; of the layers enabling finer W8A8 quantization granularity while the remaining 9737; of layers retain the per45;channel configuration. As a result the average accuracy of LLaMA345;70B45;W8A8 is increased from 45.537; to 73.437; (just 0.737; shy of LLaMA345;70B45;FP16) across eight reasoning tasks. Notably our method requires neither calibration nor fine45;tuning.
