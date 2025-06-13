---
layout: publication
title: 'Turnbench-ms: A Benchmark For Evaluating Multi-turn, Multi-step Reasoning In Large Language Models'
authors: Yiran Zhang, Mo Wang, Xiaoyang Li, Kaixuan Ren, Chencheng Zhu, Usman Naseem
conference: "Arxiv"
year: 2025
bibkey: zhang2025turnbench
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01341'}
tags: ['Reinforcement Learning']
---
Despite impressive advances in large language models (LLMs), existing benchmarks often focus on single-turn or single-step tasks, failing to capture the kind of iterative reasoning required in real-world settings. To address this limitation, we introduce TurnBench, a novel benchmark that evaluates multi-turn, multi-step reasoning through an interactive code-breaking task inspired by a "Turing Machine Board Game." In each episode, a model must uncover hidden logical or arithmetic rules by making sequential guesses, receiving structured feedback, and integrating clues across multiple rounds. This dynamic setup requires models to reason over time, adapt based on past information, and maintain consistency across steps-capabilities underexplored in current benchmarks. TurnBench includes two modes: Classic, which tests standard reasoning, and Nightmare, which introduces increased complexity and requires robust inferential chains. To support fine-grained analysis, we provide ground-truth annotations for intermediate reasoning steps. Our evaluation of state-of-the-art LLMs reveals significant gaps: the best model achieves 81.5% accuracy in Classic mode, but performance drops to 17.8% in Nightmare mode. In contrast, human participants achieve 100% in both, underscoring the challenge TurnBench poses to current models. By incorporating feedback loops and hiding task rules, TurnBench reduces contamination risks and provides a rigorous testbed for diagnosing and advancing multi-step, multi-turn reasoning in LLMs.
