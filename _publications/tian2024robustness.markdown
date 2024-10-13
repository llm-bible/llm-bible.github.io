---
layout: publication
title: 'Robustness Assessment Of Mathematical Reasoning In The Presence Of Missing And Contradictory Conditions'
authors: Tian Shi-yu, Zhou Zhi, Jia Lin-han, Guo Lan-zhe, Li Yu-feng
conference: "Arxiv"
year: 2024
bibkey: tian2024robustness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05055"}
tags: ['Few Shot', 'In Context Learning', 'Prompting', 'Reinforcement Learning', 'Security']
---
Large language models (LLMs) have demonstrated impressive performance on
reasoning tasks, which can be further improved through few-shot prompting
techniques. However, the current evaluation primarily focuses on carefully
constructed benchmarks and neglects the consideration of real-world reasoning
problems that present missing and contradictory conditions, known as
ill-defined problems. Our observations suggest that existing few-shot prompting
techniques are ineffective in such scenarios, often providing overconfident
answers or hallucination. To further study this problem, we develop a benchmark
called Problems with Missing and Contradictory conditions (PMC) and introduce
two novel metrics to evaluate the performance of few-shot prompting methods in
these scenarios. Our analysis using the PMC benchmark reveals a trade-off
dilemma between the performance of mathematical reasoning for well-defined
problems and the ability to recognize ill-defined problems. To address the
challenges posed by PMC, we propose a novel few-shot prompting method called
SMT-LIB Prompting (SLP), which utilizes the SMT-LIB language to model the
problems instead of solving them directly. Subsequently, a double-check solving
strategy checks the satisfiability and uniqueness of the solution and provides
final feedback. Extensive experiments demonstrate the superiority of our SLP
approach compared to existing few-shot prompting methods when dealing with
problems with missing and contradictory conditions. We will open-source our
benchmark and code to facilitate future research.
