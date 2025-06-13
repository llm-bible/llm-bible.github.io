---
layout: publication
title: 'Reasoning Towards Fairness: Mitigating Bias In Language Models Through Reasoning-guided Fine-tuning'
authors: Sanchit Kabra, Akshita Jha, Chandan K. Reddy
conference: "Arxiv"
year: 2025
bibkey: kabra2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05632"}
tags: ['Training Techniques', 'Fairness', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning']
---
Recent advances in large-scale generative language models have shown that
reasoning capabilities can significantly improve model performance across a
variety of tasks. However, the impact of reasoning on a model's ability to
mitigate stereotypical responses remains largely underexplored. In this work,
we investigate the crucial relationship between a model's reasoning ability and
fairness, and ask whether improved reasoning capabilities can mitigate harmful
stereotypical responses, especially those arising due to shallow or flawed
reasoning. We conduct a comprehensive evaluation of multiple open-source LLMs,
and find that larger models with stronger reasoning abilities exhibit
substantially lower stereotypical bias on existing fairness benchmarks.
Building on this insight, we introduce ReGiFT -- Reasoning Guided Fine-Tuning,
a novel approach that extracts structured reasoning traces from advanced
reasoning models and infuses them into models that lack such capabilities. We
use only general-purpose reasoning and do not require any fairness-specific
supervision for bias mitigation. Notably, we see that models fine-tuned using
ReGiFT not only improve fairness relative to their non-reasoning counterparts
but also outperform advanced reasoning models on fairness benchmarks. We also
analyze how variations in the correctness of the reasoning traces and their
length influence model fairness and their overall performance. Our findings
highlight that enhancing reasoning capabilities is an effective,
fairness-agnostic strategy for mitigating stereotypical bias caused by
reasoning flaws.
