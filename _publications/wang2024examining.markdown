---
layout: publication
title: 'FACT: Examining The Effectiveness Of Iterative Context Rewriting For Multi-fact Retrieval'
authors: Jinlin Wang, Suyuchen Wang, Ziwen Xia, Sirui Hong, Yun Zhu, Bang Liu, Chenglin Wu
conference: "Arxiv"
year: 2024
bibkey: wang2024examining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.21012"}
tags: ['Reinforcement Learning']
---
Large Language Models (LLMs) are proficient at retrieving single facts from
extended contexts, yet they struggle with tasks requiring the simultaneous
retrieval of multiple facts, especially during generation. This paper
identifies a novel "lost-in-the-middle" phenomenon, where LLMs progressively
lose track of critical information throughout the generation process, resulting
in incomplete or inaccurate retrieval. To address this challenge, we introduce
Find All Crucial Texts (FACT), an iterative retrieval method that refines
context through successive rounds of rewriting. This approach enables models to
capture essential facts incrementally, which are often overlooked in
single-pass retrieval. Experiments demonstrate that FACT substantially enhances
multi-fact retrieval performance across various tasks, though improvements are
less notable in general-purpose QA scenarios. Our findings shed light on the
limitations of LLMs in multi-fact retrieval and underscore the need for more
resilient long-context retrieval strategies.
