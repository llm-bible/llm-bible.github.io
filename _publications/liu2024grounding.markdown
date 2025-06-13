---
layout: publication
title: 'Grounding Large Language Models In Embodied Environment With Imperfect World Models'
authors: Haolan Liu, Jishen Zhao
conference: "Arxiv"
year: 2024
bibkey: liu2024grounding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02742"}
tags: ['Agentic', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Applications']
---
Despite a widespread success in various applications, large language models
(LLMs) often stumble when tackling basic physical reasoning or executing
robotics tasks, due to a lack of direct experience with the physical nuances of
the real world. To address these issues, we propose a Grounding Large language
model with Imperfect world MOdel (GLIMO), which utilizes proxy world models
such as simulators to collect and synthesize trining data. GLIMO incorporates
an LLM agent-based data generator to automatically create high-quality and
diverse instruction datasets. The generator includes an iterative self-refining
module for temporally consistent experience sampling, a diverse set of
question-answering instruction seeds, and a retrieval-augmented generation
module for reflecting on prior experiences. Comprehensive experiments show that
our approach improve the performance of strong open-source LLMs like LLaMA-3
with a performance boost of 2.04 \\(\times\\), 1.54 \\(\times\\), and 1.82 \\(\times\\)
across three different benchmarks, respectively. The performance is able to
compete with or surpass their larger counterparts such as GPT-4.
