---
layout: publication
title: 'Do LLM Evaluators Prefer Themselves For A Reason?'
authors: Wei-lin Chen, Zhepei Wei, Xinyu Zhu, Shi Feng, Yu Meng
conference: "Arxiv"
year: 2025
bibkey: chen2025do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03846"}
tags: ['GPT', 'Applications', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning']
---
Large language models (LLMs) are increasingly used as automatic evaluators in
applications such as benchmarking, reward modeling, and self-refinement. Prior
work highlights a potential self-preference bias where LLMs favor their own
generated responses, a tendency often intensifying with model size and
capability. This raises a critical question: Is self-preference detrimental, or
does it simply reflect objectively superior outputs from more capable models?
Disentangling these has been challenging due to the usage of subjective tasks
in previous studies. To address this, we investigate self-preference using
verifiable benchmarks (mathematical reasoning, factual knowledge, code
generation) that allow objective ground-truth assessment. This enables us to
distinguish harmful self-preference (favoring objectively worse responses) from
legitimate self-preference (favoring genuinely superior ones). We conduct
large-scale experiments under controlled evaluation conditions across diverse
model families (e.g., Llama, Qwen, Gemma, Mistral, Phi, GPT, DeepSeek). Our
findings reveal three key insights: (1) Better generators are better judges --
LLM evaluators' accuracy strongly correlates with their task performance, and
much of the self-preference in capable models is legitimate. (2) Harmful
self-preference persists, particularly when evaluator models perform poorly as
generators on specific task instances. Stronger models exhibit more pronounced
harmful bias when they err, though such incorrect generations are less
frequent. (3) Inference-time scaling strategies, such as generating a long
Chain-of-Thought before evaluation, effectively reduce the harmful
self-preference. These results provide a more nuanced understanding of
LLM-based evaluation and practical insights for improving its reliability.
