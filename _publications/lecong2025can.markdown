---
layout: publication
title: 'Can Llms Reason About Program Semantics? A Comprehensive Evaluation Of Llms On Formal Specification Inference'
authors: Thanh Le-cong, Bach Le, Toby Murray
conference: "Arxiv"
year: 2025
bibkey: lecong2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04779"}
tags: ['Prompting', 'Security', 'Fine-Tuning', 'Reinforcement Learning']
---
Large Language Models (LLMs) are increasingly being used to automate programming tasks. Yet, LLMs' capabilities in reasoning about program semantics are still inadequately studied, leaving significant potential for further exploration. This paper introduces FormalBench, a comprehensive benchmark designed to evaluate LLMs' reasoning abilities on program semantics, particularly via the task of synthesizing formal program specifications to assist verifying program correctness. This task requires both comprehensive reasoning over all possible program executions and the generation of precise, syntactically correct expressions that adhere to formal syntax and semantics. Using this benchmark, we evaluated the ability of LLMs in synthesizing consistent and complete specifications. Our findings show that LLMs perform well with simple control flows but struggle with more complex structures, especially loops, even with advanced prompting. Additionally, LLMs exhibit limited robustness against semantic-preserving transformations. We also highlight common failure patterns and design self-repair prompts, improving success rates by 25%.
