---
layout: publication
title: 'Ehragent: Code Empowers Large Language Models For Few-shot Complex Tabular Reasoning On Electronic Health Records'
authors: Wenqi Shi, Ran Xu, Yuchen Zhuang, Yue Yu, Jieyu Zhang, Hang Wu, Yuanda Zhu, Joyce Ho, Carl Yang, May D. Wang
conference: "Arxiv"
year: 2024
bibkey: shi2024code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07128"}
tags: ['Agentic', 'Applications', 'RAG', 'Merging', 'Reinforcement Learning', 'Agent', 'Few-Shot']
---
Large language models (LLMs) have demonstrated exceptional capabilities in
planning and tool utilization as autonomous agents, but few have been developed
for medical problem-solving. We propose EHRAgent, an LLM agent empowered with a
code interface, to autonomously generate and execute code for multi-tabular
reasoning within electronic health records (EHRs). First, we formulate an EHR
question-answering task into a tool-use planning process, efficiently
decomposing a complicated task into a sequence of manageable actions. By
integrating interactive coding and execution feedback, EHRAgent learns from
error messages and improves the originally generated code through iterations.
Furthermore, we enhance the LLM agent by incorporating long-term memory, which
allows EHRAgent to effectively select and build upon the most relevant
successful cases from past experiences. Experiments on three real-world
multi-tabular EHR datasets show that EHRAgent outperforms the strongest
baseline by up to 29.6% in success rate. EHRAgent leverages the emerging
few-shot learning capabilities of LLMs, enabling autonomous code generation and
execution to tackle complex clinical tasks with minimal demonstrations.
