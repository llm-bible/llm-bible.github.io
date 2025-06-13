---
layout: publication
title: 'Polymath: A Challenging Multi-modal Mathematical Reasoning Benchmark'
authors: Himanshu Gupta, Shreyas Verma, Ujjwala Anantheswaran, Kevin Scaria, Mihir Parmar, Swaroop Mishra, Chitta Baral
conference: "Arxiv"
year: 2024
bibkey: gupta2024challenging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14702"}
tags: ['Prompting', 'Model Architecture', 'GPT', 'Reinforcement Learning']
---
Multi-modal Large Language Models (MLLMs) exhibit impressive problem-solving
abilities in various domains, but their visual comprehension and abstract
reasoning skills remain under-evaluated. To this end, we present PolyMATH, a
challenging benchmark aimed at evaluating the general cognitive reasoning
abilities of MLLMs. PolyMATH comprises 5,000 manually collected high-quality
images of cognitive textual and visual challenges across 10 distinct
categories, including pattern recognition, spatial reasoning, and relative
reasoning. We conducted a comprehensive, and quantitative evaluation of 15
MLLMs using four diverse prompting strategies, including Chain-of-Thought and
Step-Back. The best scores achieved on PolyMATH are ~41%, ~36%, and ~27%,
obtained by Claude-3.5 Sonnet, GPT-4o and Gemini-1.5 Pro respectively -
highlighting the logical and visual complexity of these questions. A further
fine-grained error analysis reveals that these models struggle to understand
spatial relations and perform drawn-out, high-level reasoning. This is further
strengthened by our ablation study estimating MLLM performance when given
textual descriptions in place of diagrams. As evidenced by ~4% improvement over
textual descriptions as opposed to actual images, we discover that models do
not truly comprehend visual diagrams and the spatial information therein, and
are thus prone to logical errors. Finally, we evaluate the OpenAI o1 models and
find that their performance only matches the human baseline, highlighting the
difficulty of the benchmark. The results on PolyMATH highlight the room for
improvement in multi-modal reasoning and provide unique insights to guide the
development of future MLLMs.
