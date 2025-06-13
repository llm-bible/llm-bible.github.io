---
layout: publication
title: 'The Hidden Space Of Safety: Understanding Preference-tuned Llms In Multilingual Context'
authors: Nikhil Verma, Manasa Bharadwaj
conference: "Arxiv"
year: 2025
bibkey: verma2025hidden
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.02708'}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Ethics and Bias', 'Responsible AI', 'Pretraining Methods']
---
Alignment tuning has enabled large language models to excel in reasoning,
instruction-following, and minimizing harmful generations. However, despite
their widespread deployment, these models exhibit a monolingual bias, raising
concerns about the effectiveness of alignment across languages. Current
alignment methods predominantly focus on English, leaving it unclear how
alignment mechanism generalize to multilingual settings. To address this, we
conduct a systematic analysis of distributional shifts in the embedding space
of LLMs before and after alignment, uncovering its impact on model behavior
across diverse languages. We leverage the alignment-induced separation in
safety space as a quantitative tool to measure how alignment enforces safety
constraints. Our study evaluates seven LLMs using balanced toxicity datasets
and parallel text-detoxification benchmarks, revealing substantial disparities
in the latent representation space between high-resource and low-resource
languages. These findings underscore the need for language-specific fine-tuning
to ensure fair, reliable and robust multilingual alignment. Our insights
provide a foundation for developing truly safe multilingual LLMs, emphasizing
the urgency of addressing alignment gaps in underrepresented languages.
