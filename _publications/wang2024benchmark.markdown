---
layout: publication
title: 'Webquest: A Benchmark For Multimodal QA On Web Page Sequences'
authors: Maria Wang, Srinivas Sunkara, Gilles Baechler, Jason Lin, Yun Zhu, Fedir Zubach, Lei Shu, Jindong Chen
conference: "Arxiv"
year: 2024
bibkey: wang2024benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13711"}
tags: ['Agentic', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Multimodal Models', 'Prompting']
---
The rise of powerful multimodal LLMs has enhanced the viability of building
web agents which can, with increasing levels of autonomy, assist users to
retrieve information and complete tasks on various human-computer interfaces.
It is hence necessary to build challenging benchmarks that span a wide-variety
of use cases reflecting real-world usage. In this work, we present WebQuest, a
multi-page question-answering dataset that requires reasoning across multiple
related web pages. In contrast to existing UI benchmarks that focus on
multi-step web navigation and task completion, our dataset evaluates
information extraction, multimodal retrieval and composition of information
from many web pages. WebQuest includes three question categories: single-screen
QA, multi-screen QA, and QA based on navigation traces. We evaluate leading
proprietary multimodal models like GPT-4V, Gemini Flash, Claude 3, and open
source models like InstructBLIP, PaliGemma on our dataset, revealing a
significant gap between single-screen and multi-screen reasoning. Finally, we
investigate inference time techniques like Chain-of-Thought prompting to
improve model capabilities on multi-screen reasoning.
