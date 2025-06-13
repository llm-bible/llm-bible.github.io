---
layout: publication
title: 'Proof Or Bluff? Evaluating Llms On 2025 USA Math Olympiad'
authors: Ivo Petrov, Jasper Dekoninck, Lyuben Baltadzhiev, Maria Drencheva, Kristian Minchev, Mislav Balunović, Nikola Jovanović, Martin Vechev
conference: "Arxiv"
year: 2025
bibkey: petrov2025proof
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.21934"}
tags: ['Training Techniques', 'Tools', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Recent math benchmarks for large language models (LLMs) such as MathArena
indicate that state-of-the-art reasoning models achieve impressive performance
on mathematical competitions like AIME, with the leading model, Gemini-2.5-Pro,
achieving scores comparable to top human competitors. However, these benchmarks
evaluate models solely based on final numerical answers, neglecting rigorous
reasoning and proof generation which are essential for real-world mathematical
tasks. To address this, we introduce the first comprehensive evaluation of
full-solution reasoning for challenging mathematical problems. Using expert
human annotators, we evaluated several state-of-the-art reasoning models on the
six problems from the 2025 USAMO within hours of their release. Our results
reveal that all tested models struggled significantly: only Gemini-2.5-Pro
achieves a non-trivial score of 25%, while all other models achieve less than
5%. Through detailed analysis of reasoning traces, we identify the most common
failure modes and find several unwanted artifacts arising from the optimization
strategies employed during model training. Overall, our results suggest that
current LLMs are inadequate for rigorous mathematical reasoning tasks,
highlighting the need for substantial improvements in reasoning and proof
generation capabilities.
