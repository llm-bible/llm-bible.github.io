---
layout: publication
title: 'Understanding Before Reasoning: Enhancing Chain-of-thought With Iterative Summarization Pre-prompting'
authors: Dong-hai Zhu, Yu-jie Xiong, Jia-chen Zhang, Xi-jiong Xie, Chun-ming Xia
conference: "Arxiv"
year: 2025
bibkey: zhu2025understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.04341'}
  - {name: "Code", url: 'https://github.com/zdhgreat/ISP-2'}
tags: ['Has Code', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Chain-of-Thought (CoT) Prompting is a dominant paradigm in Large Language
Models (LLMs) to enhance complex reasoning. It guides LLMs to present
multi-step reasoning, rather than generating the final answer directly.
However, CoT encounters difficulties when key information required for
reasoning is implicit or missing. This occurs because CoT emphasizes the
sequence of reasoning steps while overlooking the early extraction of essential
information. We propose a pre-prompting method called Iterative Summarization
Pre-Prompting (ISP^2) to refine LLM reasoning when key information is not
explicitly provided. First, entities and their corresponding descriptions are
extracted to form potential key information pairs. Next, we use a reliability
rating to assess these pairs, then merge the two lowest-ranked pairs into a new
entity description. This process is repeated until a unique key information
pair is obtained. Finally, that pair, along with the original question, is fed
into LLMs to produce the answer. Extensive experiments demonstrate a 7.1%
improvement compared to existing methods. Unlike traditional prompting, ISP^2
adopts an inductive approach with pre-prompting, offering flexible integration
into diverse reasoning frameworks. The code is available at
https://github.com/zdhgreat/ISP-2.
