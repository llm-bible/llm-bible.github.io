---
layout: publication
title: 'Memory-enhanced Retrieval Augmentation For Long Video Understanding'
authors: Huaying Yuan, Zheng Liu, Minhao Qin, Hongjin Qian, Y Shu, Zhicheng Dou, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: yuan2025memory
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.09149'}
tags: ['Reinforcement Learning', 'RAG', 'Agentic']
---
Retrieval-augmented generation (RAG) shows strong potential in addressing
long-video understanding (LVU) tasks. However, traditional RAG methods remain
fundamentally limited due to their dependence on explicit search queries, which
are unavailable in many situations. To overcome this challenge, we introduce a
novel RAG-based LVU approach inspired by the cognitive memory of human beings,
which is called MemVid. Our approach operates with four basics steps:
memorizing holistic video information, reasoning about the task's information
needs based on the memory, retrieving critical moments based on the information
needs, and focusing on the retrieved moments to produce the final answer. To
enhance the system's memory-grounded reasoning capabilities and achieve optimal
end-to-end performance, we propose a curriculum learning strategy. This
approach begins with supervised learning on well-annotated reasoning results,
then progressively explores and reinforces more plausible reasoning outcomes
through reinforcement learning. We perform extensive evaluations on popular LVU
benchmarks, including MLVU, VideoMME and LVBench. In our experiment, MemVid
significantly outperforms existing RAG-based methods and popular LVU models,
which demonstrate the effectiveness of our approach. Our model and source code
will be made publicly available upon acceptance.
