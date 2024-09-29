---
layout: publication
title: Mg45;verilog Multi45;grained Dataset Towards Enhanced Llm45;assisted Verilog Generation
authors: Zhang Yongan, Yu Zhongzhi, Fu Yonggan, Wan Cheng, Lin Yingyan Celine
conference: "Arxiv"
year: 2024
bibkey: zhang2024mg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01910"}
tags: ['Applications', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) have recently shown promise in streamlining hardware design processes by encapsulating vast amounts of domain45;specific data. In addition they allow users to interact with the design processes through natural language instructions thus making hardware design more accessible to developers. However effectively leveraging LLMs in hardware design necessitates providing domain45;specific data during inference (e.g. through in45;context learning) fine45;tuning or pre45;training. Unfortunately existing publicly available hardware datasets are often limited in size complexity or detail which hinders the effectiveness of LLMs in hardware design tasks. To address this issue we first propose a set of criteria for creating high45;quality hardware datasets that can effectively enhance LLM45;assisted hardware design. Based on these criteria we propose a Multi45;Grained45;Verilog (MG45;Verilog) dataset which encompasses descriptions at various levels of detail and corresponding code samples. To benefit the broader hardware design community we have developed an open45;source infrastructure that facilitates easy access integration and extension of the dataset to meet specific project needs. Furthermore to fully exploit the potential of the MG45;Verilog dataset which varies in complexity and detail we introduce a balanced fine45;tuning scheme. This scheme serves as a unique use case to leverage the diverse levels of detail provided by the dataset. Extensive experiments demonstrate that the proposed dataset and fine45;tuning scheme consistently improve the performance of LLMs in hardware design tasks.
