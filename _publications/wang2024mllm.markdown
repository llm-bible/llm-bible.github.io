---
layout: publication
title: Mllm45;tool A Multimodal Large Language Model For Tool Agent Learning
authors: Wang Chenyu Michael, Luo Weixin Michael, Chen Qianyu Michael, Mai Haonan Michael, Guo Jindi Michael, Dong Sixun Michael, Xiaohua Michael, Xuan, Li Zhengxin, Ma Lin, Gao Shenghua
conference: "Arxiv"
year: 2024
bibkey: wang2024mllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10727"}
  - {name: "Code", url: "https://github.com/MLLM&#45;Tool/MLLM&#45;Tool"}
tags: ['Agentic', 'Fine Tuning', 'Has Code', 'Multimodal Models', 'Tools']
---
Recently the astonishing performance of large language models (LLMs) in natural language comprehension and generation tasks triggered lots of exploration of using them as central controllers to build agent systems. Multiple studies focus on bridging the LLMs to external tools to extend the application scenarios. However the current LLMs perceiving tool45;use ability is limited to a single text query which may result in ambiguity in understanding the users real intentions. LLMs are expected to eliminate that by perceiving the visual45; or auditory45;grounded instructions information. Therefore in this paper we propose MLLM45;Tool a system incorporating open45;source LLMs and multi45;modal encoders so that the learnt LLMs can be conscious of multi45;modal input instruction and then select the function45;matched tool correctly. To facilitate the evaluation of the models capability we collect a dataset featured by consisting of multi45;modal input tools from HuggingFace. Another important feature of our dataset is that our dataset also contains multiple potential choices for the same instruction due to the existence of identical functions and synonymous functions which provides more potential solutions for the same query. The experiments reveal that our MLLM45;Tool is capable of recommending appropriate tools for multi45;modal instructions. Codes and data are available at https://github.com/MLLM&#45;Tool/MLLM&#45;Tool.
