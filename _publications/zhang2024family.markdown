---
layout: publication
title: 'Xlam: A Family Of Large Action Models To Empower AI Agent Systems'
authors: Jianguo Zhang, Tian Lan, Ming Zhu, Zuxin Liu, Thai Hoang, Shirley Kokane, Weiran Yao, Juntao Tan, Akshara Prabhakar, Haolin Chen, Zhiwei Liu, Yihao Feng, Tulika Awalgaonkar, Rithesh Murthy, Eric Hu, Zeyuan Chen, Ran Xu, Juan Carlos Niebles, Shelby Heinecke, Huan Wang, Silvio Savarese, Caiming Xiong
conference: "Arxiv"
year: 2024
bibkey: zhang2024family
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03215"}
tags: ['Agentic', 'GPT', 'Agent', 'Model Architecture']
---
Autonomous agents powered by large language models (LLMs) have attracted
significant research interest. However, the open-source community faces many
challenges in developing specialized models for agent tasks, driven by the
scarcity of high-quality agent datasets and the absence of standard protocols
in this area. We introduce and publicly release xLAM, a series of large action
models designed for AI agent tasks. The xLAM series includes five models with
both dense and mixture-of-expert architectures, ranging from 1B to 8x22B
parameters, trained using a scalable, flexible pipeline that unifies, augments,
and synthesizes diverse datasets to enhance AI agents' generalizability and
performance across varied environments. Our experimental results demonstrate
that xLAM consistently delivers exceptional performance across multiple agent
ability benchmarks, notably securing the 1st position on the Berkeley
Function-Calling Leaderboard, outperforming GPT-4, Claude-3, and many other
models in terms of tool use. By releasing the xLAM series, we aim to advance
the performance of open-source LLMs for autonomous AI agents, potentially
accelerating progress and democratizing access to high-performance models for
agent tasks. Models are available at
https://huggingface.co/collections/Salesforce/xlam-models-65f00e2a0a63bbcd1c2dade4
