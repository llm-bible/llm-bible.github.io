---
layout: publication
title: 'Mdocagent: A Multi-modal Multi-agent Framework For Document Understanding'
authors: Siwei Han, Peng Xia, Ruiyi Zhang, Tong Sun, Yun Li, Hongtu Zhu, Huaxiu Yao
conference: "Arxiv"
year: 2025
bibkey: han2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13964"}
  - {name: "Code", url: "https://github.com/aiming-lab/MDocAgent"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Applications']
---
Document Question Answering (DocQA) is a very common task. Existing methods
using Large Language Models (LLMs) or Large Vision Language Models (LVLMs) and
Retrieval Augmented Generation (RAG) often prioritize information from a single
modal, failing to effectively integrate textual and visual cues. These
approaches struggle with complex multi-modal reasoning, limiting their
performance on real-world documents. We present MDocAgent (A Multi-Modal
Multi-Agent Framework for Document Understanding), a novel RAG and multi-agent
framework that leverages both text and image. Our system employs five
specialized agents: a general agent, a critical agent, a text agent, an image
agent and a summarizing agent. These agents engage in multi-modal context
retrieval, combining their individual insights to achieve a more comprehensive
understanding of the document's content. This collaborative approach enables
the system to synthesize information from both textual and visual components,
leading to improved accuracy in question answering. Preliminary experiments on
five benchmarks like MMLongBench, LongDocURL demonstrate the effectiveness of
our MDocAgent, achieve an average improvement of 12.1% compared to current
state-of-the-art method. This work contributes to the development of more
robust and comprehensive DocQA systems capable of handling the complexities of
real-world documents containing rich textual and visual information. Our data
and code are available at https://github.com/aiming-lab/MDocAgent.
