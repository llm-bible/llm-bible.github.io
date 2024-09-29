---
layout: publication
title: LLMC\: Benchmarking Large Language Model Quantization With A Versatile Compression Toolkit
authors: Gong Ruihao, Yong Yang, Gu Shiqiao, Huang Yushi, Lv Chentao, Zhang Yunchen, Liu Xianglong, Tao Dacheng
conference: "Arxiv"
year: 2024
bibkey: gong2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06001"}
  - {name: "Code", url: "https://github.com/ModelTC/llmc"}
tags: ['Efficiency And Optimization', 'Has Code', 'Multimodal Models', 'Pruning', 'Quantization', 'Reinforcement Learning', 'Training Techniques']
---
Recent advancements in large language models (LLMs) are propelling us toward artificial general intelligence with their remarkable emergent abilities and reasoning capabilities. However the substantial computational and memory requirements limit the widespread adoption. Quantization a key compression technique can effectively mitigate these demands by compressing and accelerating LLMs albeit with potential risks to accuracy. Numerous studies have aimed to minimize the accuracy loss associated with quantization. However their quantization configurations vary from each other and cannot be fairly compared. In this paper we present LLMC a plug-and-play compression toolkit to fairly and systematically explore the impact of quantization. LLMC integrates dozens of algorithms models and hardwares offering high extensibility from integer to floating-point quantization from LLM to vision-language (VLM) model from fixed-bit to mixed precision and from quantization to sparsification. Powered by this versatile toolkit our benchmark covers three key aspects calibration data algorithms (three strategies) and data formats providing novel insights and detailed analyses for further research and practical guidance for users. Our toolkit is available at (hrefLLMC)https://github.com/ModelTC/llmc\}."
