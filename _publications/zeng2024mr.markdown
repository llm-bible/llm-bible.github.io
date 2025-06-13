---
layout: publication
title: 'Mr-ben: A Meta-reasoning Benchmark For Evaluating System-2 Thinking In Llms'
authors: Zhongshen Zeng, Yinhong Liu, Yingjia Wan, Jingyao Li, Pengguang Chen, Jianbo Dai, Yuxuan Yao, Rongwu Xu, Zehan Qi, Wanru Zhao, Linling Shen, Jianqiao Lu, Haochen Tan, Yukang Chen, Hao Zhang, Zhan Shi, Bailin Wang, Zhijiang Guo, Jiaya Jia
conference: "Arxiv"
year: 2024
bibkey: zeng2024mr
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.13975'}
tags: ['Training Techniques']
---
Large language models (LLMs) have shown increasing capability in
problem-solving and decision-making, largely based on the step-by-step
chain-of-thought reasoning processes. However, evaluating these reasoning
abilities has become increasingly challenging. Existing outcome-based
benchmarks are beginning to saturate, becoming less effective in tracking
meaningful progress. To address this, we present a process-based benchmark
MR-Ben that demands a meta-reasoning skill, where LMs are asked to locate and
analyse potential errors in automatically generated reasoning steps. Our
meta-reasoning paradigm is especially suited for system-2 slow thinking,
mirroring the human cognitive process of carefully examining assumptions,
conditions, calculations, and logic to identify mistakes.MR-Ben comprises 5,975
questions curated by human experts across a wide range of subjects, including
physics, chemistry, logic, coding, and more. Through our designed metrics for
assessing meta-reasoning on this benchmark, we identify interesting limitations
and weaknesses of current LLMs (open-source and closed-source models). For
example, with models like the o1 series from OpenAI demonstrating strong
performance by effectively scrutinizing the solution space, many other
state-of-the-art models fall significantly behind on MR-Ben, exposing potential
shortcomings in their training strategies and inference methodologies.
