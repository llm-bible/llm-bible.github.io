---
layout: publication
title: Semcoder: Training Code Language Models With Comprehensive Semantics
authors: Ding Yangruibo, Peng Jinjun, Min Marcus J., Kaiser Gail, Yang Junfeng, Ray Baishakhi
conference: "Arxiv"
year: 2024
bibkey: ding2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01006"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Training Techniques']
---
Code Large Language Models (Code LLMs) have excelled at tasks like code completion but often miss deeper semantics such as execution effects and dynamic states. This paper aims to bridge the gap between Code LLMs reliance on static text data and the need for thorough semantic understanding for complex tasks like debugging and program repair. We introduce a novel strategy to train Code LLMs with comprehensive semantics encompassing high-level functional descriptions local execution effects of individual statements and overall input/output behavior thereby linking static code text with dynamic execution states. We begin by collecting PyX a clean code corpus of fully executable samples with functional descriptions and execution tracing. We propose training Code LLMs to write code and represent and reason about execution behaviors using natural language mimicking human verbal debugging. This approach led to the development of SemCoder a Code LLM with only 6.7B parameters which shows competitive performance with GPT-3.5-turbo on code generation and execution reasoning tasks. SemCoder achieves 81.137; on HumanEval (GPT-3.5-turbo 76.837;) and 54.537; on CRUXEval-I (GPT-3.5-turbo 50.337;). We also study the effectiveness of SemCoders monologue-style execution reasoning compared to concrete scratchpad reasoning showing that our approach integrates semantics from multiple dimensions more smoothly. Finally we demonstrate the potential of applying learned semantics to improve Code LLMs debugging and self-refining capabilities.
