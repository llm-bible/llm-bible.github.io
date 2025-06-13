---
layout: publication
title: 'The Labyrinth Of Links: Navigating The Associative Maze Of Multi-modal Llms'
authors: Hong Li, Nanxi Li, Yuanjie Chen, Jianbin Zhu, Qinlu Guo, Cewu Lu, Yong-lu Li
conference: "Arxiv"
year: 2024
bibkey: li2024labyrinth
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01417"}
  - {name: "Code", url: "https://mvig-rhos.com/llm_inception"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Merging', 'GPT', 'Has Code']
---
Multi-modal Large Language Models (MLLMs) have exhibited impressive
capability. However, recently many deficiencies of MLLMs have been found
compared to human intelligence, \\(\textit\{e.g.\}\\), hallucination. To drive the
MLLMs study, the community dedicated efforts to building larger benchmarks with
complex tasks. In this paper, we propose benchmarking an essential but usually
overlooked intelligence: \\(\textbf\{association\}\\), a human's basic capability to
link observation and prior practice memory. To comprehensively investigate
MLLM's performance on the association, we formulate the association task and
devise a standard benchmark based on adjective and verb semantic concepts.
Instead of costly data annotation and curation, we propose a convenient
\\(\textbf\{annotation-free\}\\) construction method transforming the general dataset
for our association tasks. Simultaneously, we devise a rigorous data refinement
process to eliminate confusion in the raw dataset. Building on this database,
we establish three levels of association tasks: single-step, synchronous, and
asynchronous associations. Moreover, we conduct a comprehensive investigation
into the MLLMs' zero-shot association capabilities, addressing multiple
dimensions, including three distinct memory strategies, both open-source and
closed-source MLLMs, cutting-edge Mixture-of-Experts (MoE) models, and the
involvement of human experts. Our systematic investigation shows that current
open-source MLLMs consistently exhibit poor capability in our association
tasks, even the currently state-of-the-art GPT-4V(vision) also has a
significant gap compared to humans. We believe our benchmark would pave the way
for future MLLM studies. \\(\textit\{Our data and code are available at:\}\\)
https://mvig-rhos.com/llm_inception.
