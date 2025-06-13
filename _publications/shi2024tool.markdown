---
layout: publication
title: 'Tool Learning In The Wild: Empowering Language Models As Automatic Tool Agents'
authors: Zhengliang Shi, Shen Gao, Lingyong Yan, Yue Feng, Xiuyi Chen, Zhumin Chen, Dawei Yin, Suzan Verberne, Zhaochun Ren
conference: "Arxiv"
year: 2024
bibkey: shi2024tool
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16533"}
tags: ['Training Techniques', 'Agentic', 'Reinforcement Learning', 'Tools']
---
Augmenting large language models (LLMs) with external tools has emerged as a
promising approach to extend their utility, enabling them to solve practical
tasks. Previous methods manually parse tool documentation and create in-context
demonstrations, transforming tools into structured formats for LLMs to use in
their step-by-step reasoning. However, this manual process requires domain
expertise and struggles to scale to large toolsets. Additionally, these methods
rely heavily on ad-hoc inference techniques or special tokens to integrate
free-form LLM generation with tool-calling actions, limiting the LLM's
flexibility in handling diverse tool specifications and integrating multiple
tools.
  In this work, we propose AutoTools, a framework that enables LLMs to automate
the tool-use workflow. Specifically, the LLM automatically transforms tool
documentation into callable functions, verifying syntax and runtime
correctness. Then, the LLM integrates these functions into executable programs
to solve practical tasks, flexibly grounding tool-use actions into its
reasoning processes. Extensive experiments on existing and newly collected,
more challenging benchmarks illustrate the superiority of our framework.
Inspired by these promising results, we further investigate how to improve the
expertise of LLMs, especially open-source LLMs with fewer parameters, within
AutoTools. Thus, we propose the AutoTools-learning approach, training the LLMs
with three learning tasks on 34k instances of high-quality synthetic data,
including documentation understanding, relevance learning, and function
programming. Fine-grained results validate the effectiveness of our overall
training approach and each individual task. Our methods are an important step
towards the use of LLMs for solving real-world tasks with external tools.
