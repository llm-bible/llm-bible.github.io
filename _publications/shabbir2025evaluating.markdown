---
layout: publication
title: 'Thinkgeo: Evaluating Tool-augmented Agents For Remote Sensing Tasks'
authors: Akashah Shabbir, Muhammad Akhtar Munir, Akshay Dudhane, Muhammad Umer Sheikh, Muhammad Haris Khan, Paolo Fraccaro, Juan Bernabe Moreno, Fahad Shahbaz Khan, Salman Khan
conference: "Arxiv"
year: 2025
bibkey: shabbir2025evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23752'}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Applications', 'GPT', 'Multimodal Models', 'Reinforcement Learning']
---
Recent progress in large language models (LLMs) has enabled tool-augmented agents capable of solving complex real-world tasks through step-by-step reasoning. However, existing evaluations often focus on general-purpose or multimodal scenarios, leaving a gap in domain-specific benchmarks that assess tool-use capabilities in complex remote sensing use cases. We present ThinkGeo, an agentic benchmark designed to evaluate LLM-driven agents on remote sensing tasks via structured tool use and multi-step planning. Inspired by tool-interaction paradigms, ThinkGeo includes human-curated queries spanning a wide range of real-world applications such as urban planning, disaster assessment and change analysis, environmental monitoring, transportation analysis, aviation monitoring, recreational infrastructure, and industrial site analysis. Each query is grounded in satellite or aerial imagery and requires agents to reason through a diverse toolset. We implement a ReAct-style interaction loop and evaluate both open and closed-source LLMs (e.g., GPT-4o, Qwen2.5) on 436 structured agentic tasks. The benchmark reports both step-wise execution metrics and final answer correctness. Our analysis reveals notable disparities in tool accuracy and planning consistency across models. ThinkGeo provides the first extensive testbed for evaluating how tool-enabled LLMs handle spatial reasoning in remote sensing. Our code and dataset are publicly available
