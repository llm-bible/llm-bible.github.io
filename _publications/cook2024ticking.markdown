---
layout: publication
title: 'Ticking All The Boxes: Generated Checklists Improve LLM Evaluation And Generation'
authors: Jonathan Cook, Tim Rocktäschel, Jakob Foerster, Dennis Aumiller, Alex Wang
conference: "Arxiv"
year: 2024
bibkey: cook2024ticking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03608"}
tags: ['Interpretability and Explainability', 'Reinforcement Learning']
---
Given the widespread adoption and usage of Large Language Models (LLMs), it
is crucial to have flexible and interpretable evaluations of their
instruction-following ability. Preference judgments between model outputs have
become the de facto evaluation standard, despite distilling complex,
multi-faceted preferences into a single ranking. Furthermore, as human
annotation is slow and costly, LLMs are increasingly used to make these
judgments, at the expense of reliability and interpretability. In this work, we
propose TICK (Targeted Instruct-evaluation with ChecKlists), a fully automated,
interpretable evaluation protocol that structures evaluations with
LLM-generated, instruction-specific checklists. We first show that, given an
instruction, LLMs can reliably produce high-quality, tailored evaluation
checklists that decompose the instruction into a series of YES/NO questions.
Each question asks whether a candidate response meets a specific requirement of
the instruction. We demonstrate that using TICK leads to a significant increase
(46.4% \\(\to\\) 52.2%) in the frequency of exact agreements between LLM judgements
and human preferences, as compared to having an LLM directly score an output.
We then show that STICK (Self-TICK) can be used to improve generation quality
across multiple benchmarks via self-refinement and Best-of-N selection. STICK
self-refinement on LiveBench reasoning tasks leads to an absolute gain of
\\(+\\)7.8%, whilst Best-of-N selection with STICK attains \\(+\\)6.3% absolute
improvement on the real-world instruction dataset, WildBench. In light of this,
structured, multi-faceted self-improvement is shown to be a promising way to
further advance LLM capabilities. Finally, by providing LLM-generated
checklists to human evaluators tasked with directly scoring LLM responses to
WildBench instructions, we notably increase inter-annotator agreement (0.194
\\(\to\\) 0.256).
