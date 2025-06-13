---
layout: publication
title: 'Forget What You Know About Llms Evaluations -- Llms Are Like A Chameleon'
authors: Nurit Cohen-inger, Yehonatan Elisha, Bracha Shapira, Lior Rokach, Seffi Cohen
conference: "Arxiv"
year: 2025
bibkey: coheninger2025forget
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07445"}
tags: ['Prompting', 'RAG', 'Training Techniques', 'Tools']
---
Large language models (LLMs) often appear to excel on public benchmarks, but
these high scores may mask an overreliance on dataset-specific surface cues
rather than true language understanding. We introduce the Chameleon Benchmark
Overfit Detector (C-BOD), a meta-evaluation framework that systematically
distorts benchmark prompts via a parametric transformation and detects
overfitting of LLMs. By rephrasing inputs while preserving their semantic
content and labels, C-BOD exposes whether a model's performance is driven by
memorized patterns. Evaluated on the MMLU benchmark using 26 leading LLMs, our
method reveals an average performance degradation of 2.15% under modest
perturbations, with 20 out of 26 models exhibiting statistically significant
differences. Notably, models with higher baseline accuracy exhibit larger
performance differences under perturbation, and larger LLMs tend to be more
sensitive to rephrasings indicating that both cases may overrely on fixed
prompt patterns. In contrast, the Llama family and models with lower baseline
accuracy show insignificant degradation, suggesting reduced dependency on
superficial cues. Moreover, C-BOD's dataset- and model-agnostic design allows
easy integration into training pipelines to promote more robust language
understanding. Our findings challenge the community to look beyond leaderboard
scores and prioritize resilience and generalization in LLM evaluation.
