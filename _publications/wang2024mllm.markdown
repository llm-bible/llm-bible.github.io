---
layout: publication
title: 'Mllm-tool: A Multimodal Large Language Model For Tool Agent Learning'
authors: Chenyu Wang, Weixin Luo, Sixun Dong, Xiaohua Xuan, Zhengxin Li, Lin Ma, Shenghua Gao
conference: "Arxiv"
year: 2024
bibkey: wang2024mllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10727"}
  - {name: "Code", url: "https://github.com/MLLM-Tool/MLLM-Tool"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Has Code', 'Multimodal Models']
---
Recently, the astonishing performance of large language models (LLMs) in
natural language comprehension and generation tasks triggered lots of
exploration of using them as central controllers to build agent systems.
Multiple studies focus on bridging the LLMs to external tools to extend the
application scenarios. However, the current LLMs' ability to perceive tool use
is limited to a single text query, which may result in ambiguity in
understanding the users' real intentions. LLMs are expected to eliminate that
by perceiving the information in the visual- or auditory-grounded instructions.
Therefore, in this paper, we propose MLLM-Tool, a system incorporating
open-source LLMs and multi-modal encoders so that the learned LLMs can be
conscious of multi-modal input instruction and then select the function-matched
tool correctly. To facilitate the evaluation of the model's capability, we
collect a dataset featuring multi-modal input tools from HuggingFace. Another
essential feature of our dataset is that it also contains multiple potential
choices for the same instruction due to the existence of identical functions
and synonymous functions, which provides more potential solutions for the same
query. The experiments reveal that our MLLM-Tool is capable of recommending
appropriate tools for multi-modal instructions. Codes and data are available at
https://github.com/MLLM-Tool/MLLM-Tool.
