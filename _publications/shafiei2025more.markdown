---
layout: publication
title: 'More Or Less Wrong: A Benchmark For Directional Bias In LLM Comparative Reasoning'
authors: Mohammadamin Shafiei, Hamidreza Saffari, Nafise Sadat Moosavi
conference: "Arxiv"
year: 2025
bibkey: shafiei2025more
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03923"}
tags: ['Ethics and Bias', 'Bias Mitigation', 'Reinforcement Learning', 'Security', 'Fairness', 'Prompting']
---
Large language models (LLMs) are known to be sensitive to input phrasing, but the mechanisms by which semantic cues shape reasoning remain poorly understood. We investigate this phenomenon in the context of comparative math problems with objective ground truth, revealing a consistent and directional framing bias: logically equivalent questions containing the words ``more'', ``less'', or ``equal'' systematically steer predictions in the direction of the framing term. To study this effect, we introduce MathComp, a controlled benchmark of 300 comparison scenarios, each evaluated under 14 prompt variants across three LLM families. We find that model errors frequently reflect linguistic steering, systematic shifts toward the comparative term present in the prompt. Chain-of-thought prompting reduces these biases, but its effectiveness varies: free-form reasoning is more robust, while structured formats may preserve or reintroduce directional drift. Finally, we show that including demographic identity terms (e.g., ``a woman'', ``a Black person'') in input scenarios amplifies directional drift, despite identical underlying quantities, highlighting the interplay between semantic framing and social referents. These findings expose critical blind spots in standard evaluation and motivate framing-aware benchmarks for diagnosing reasoning robustness and fairness in LLMs.
