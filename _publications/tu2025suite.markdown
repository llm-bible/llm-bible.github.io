---
layout: publication
title: 'Vilbench: A Suite For Vision-language Process Reward Modeling'
authors: Haoqin Tu, Weitao Feng, Hardy Chen, Hui Liu, Xianfeng Tang, Cihang Xie
conference: "Arxiv"
year: 2025
bibkey: tu2025suite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20271"}
  - {name: "Code", url: "https://ucsc-vlaa.github.io/ViLBench"}
tags: ['Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Has Code']
---
Process-supervised reward models serve as a fine-grained function that
provides detailed step-wise feedback to model responses, facilitating effective
selection of reasoning trajectories for complex tasks. Despite its advantages,
evaluation on PRMs remains less explored, especially in the multimodal domain.
To address this gap, this paper first benchmarks current vision large language
models (VLLMs) as two types of reward models: output reward models (ORMs) and
process reward models (PRMs) on multiple vision-language benchmarks, which
reveal that neither ORM nor PRM consistently outperforms across all tasks, and
superior VLLMs do not necessarily yield better rewarding performance. To
further advance evaluation, we introduce ViLBench, a vision-language benchmark
designed to require intensive process reward signals. Notably, OpenAI's GPT-4o
with Chain-of-Thought (CoT) achieves only 27.3% accuracy, indicating the
benchmark's challenge for current VLLMs. Lastly, we preliminarily showcase a
promising pathway towards bridging the gap between general VLLMs and reward
models -- by collecting 73.6K vision-language process reward data using an
enhanced tree-search algorithm, our 3B model is able to achieve an average
improvement of 3.3% over standard CoT and up to 2.5% compared to its untrained
counterpart on ViLBench by selecting OpenAI o1's generations. We release the
implementations at https://ucsc-vlaa.github.io/ViLBench with our code, model,
and data.
