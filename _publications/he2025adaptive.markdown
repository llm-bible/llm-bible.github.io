---
layout: publication
title: 'Adaptmi: Adaptive Skill-based In-context Math Instruction For Small Language Models'
authors: Yinghui He, Abhishek Panigrahi, Yong Lin, Sanjeev Arora
conference: "Arxiv"
year: 2025
bibkey: he2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00147"}
tags: ['Prompting', 'RAG', 'In-Context Learning', 'Reinforcement Learning']
---
In-context learning (ICL) allows a language model to improve its
problem-solving capability when provided with suitable information in context.
Since the choice of in-context information can be determined based on the
problem itself, in-context learning is analogous to human learning from
teachers in a classroom. Recent works (Didolkar et al., 2024a; 2024b) show that
ICL performance can be improved by leveraging a frontier large language model's
(LLM) ability to predict required skills to solve a problem, popularly referred
to as an LLM's metacognition, and using the recommended skills to construct
necessary in-context examples. While this skill-based strategy boosts ICL
performance in larger models, its gains on small language models (SLMs) have
been minimal, highlighting a performance gap in ICL capabilities. We
investigate this gap and show that skill-based prompting can hurt SLM
performance on easy questions by introducing unnecessary information, akin to
cognitive overload. To address this, we introduce AdaptMI, an adaptive approach
to selecting skill-based in-context Math Instructions for SLMs. Inspired by
cognitive load theory from human pedagogy, our method only introduces
skill-based examples when the model performs poorly. We further propose
AdaptMI+, which adds examples targeted to the specific skills missing from the
model's responses. On 5-shot evaluations across popular math benchmarks and
five SLMs (1B--7B; Qwen, Llama), AdaptMI+ improves accuracy by up to 6% over
naive skill-based strategies.
