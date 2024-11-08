---
layout: publication
title: 'Toolllm: Facilitating Large Language Models To Master 16000+ Real-world Apis'
authors: Qin Yujia, Liang Shihao, Ye Yining, Zhu Kunlun, Yan Lan, Lu Yaxi, Lin Yankai, Cong Xin, Tang Xiangru, Qian Bill, Zhao Sihan, Hong Lauren, Tian Runchu, Xie Ruobing, Zhou Jie, Gerstein Mark, Li Dahai, Liu Zhiyuan, Sun Maosong
conference: "Arxiv"
year: 2023
bibkey: qin2023facilitating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.16789"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Despite the advancements of open-source large language models (LLMs), e.g.,
LLaMA, they remain significantly limited in tool-use capabilities, i.e., using
external tools (APIs) to fulfill human instructions. The reason is that current
instruction tuning largely focuses on basic language tasks but ignores the
tool-use domain. This is in contrast to the excellent tool-use capabilities of
state-of-the-art (SOTA) closed-source LLMs, e.g., ChatGPT. To bridge this gap,
we introduce ToolLLM, a general tool-use framework encompassing data
construction, model training, and evaluation. We first present ToolBench, an
instruction-tuning dataset for tool use, which is constructed automatically
using ChatGPT. Specifically, the construction can be divided into three stages:
(i) API collection: we collect 16,464 real-world RESTful APIs spanning 49
categories from RapidAPI Hub; (ii) instruction generation: we prompt ChatGPT to
generate diverse instructions involving these APIs, covering both single-tool
and multi-tool scenarios; (iii) solution path annotation: we use ChatGPT to
search for a valid solution path (chain of API calls) for each instruction. To
enhance the reasoning capabilities of LLMs, we develop a novel depth-first
search-based decision tree algorithm. It enables LLMs to evaluate multiple
reasoning traces and expand the search space. Moreover, to evaluate the
tool-use capabilities of LLMs, we develop an automatic evaluator: ToolEval.
Based on ToolBench, we fine-tune LLaMA to obtain an LLM ToolLLaMA, and equip it
with a neural API retriever to recommend appropriate APIs for each instruction.
Experiments show that ToolLLaMA demonstrates a remarkable ability to execute
complex instructions and generalize to unseen APIs, and exhibits comparable
performance to ChatGPT. Our ToolLLaMA also demonstrates strong zero-shot
generalization ability in an out-of-distribution tool-use dataset: APIBench.
