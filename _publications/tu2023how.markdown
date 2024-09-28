---
layout: publication
title: How Many Unicorns Are in This Image A Safety Evaluation Benchmark for Vision LLMs
authors: Tu Haoqin, Cui Chenhang, Wang Zijun, Zhou Yiyang, Zhao Bingchen, Han Junlin, Zhou Wangchunshu, Yao Huaxiu, Xie Cihang
conference: "Arxiv"
year: 2023
bibkey: tu2023how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16101"}
  - {name: "Code", url: "https://github.com/UCSC-VLAA/vllm-safety-benchmark"}
tags: ['ARXIV', 'GPT', 'Has Code', 'LLM', 'Multimodal Models', 'Responsible AI', 'Security']
---
This work focuses on the potential of Vision LLMs (VLLMs) in visual reasoning. Different from prior studies we shift our focus from evaluating standard performance to introducing a comprehensive safety evaluation suite covering both out-of-distribution (OOD) generalization and adversarial robustness. For the OOD evaluation we present two novel VQA datasets each with one variant designed to test model performance under challenging conditions. In exploring adversarial robustness we propose a straightforward attack strategy for misleading VLLMs to produce visual-unrelated responses. Moreover we assess the efficacy of two jailbreaking strategies targeting either the vision or language component of VLLMs. Our evaluation of 21 diverse models ranging from open-source VLLMs to GPT-4V yields interesting observations 1) Current VLLMs struggle with OOD texts but not images unless the visual information is limited; and 2) These VLLMs can be easily misled by deceiving vision encoders only and their vision-language training often compromise safety protocols. We release this safety evaluation suite at https://github.com/UCSC-VLAA/vllm-safety-benchmark.
