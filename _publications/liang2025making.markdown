---
layout: publication
title: 'Making Better Mistakes In Clip-based Zero-shot Classification With Hierarchy-aware Language Prompts'
authors: Tong Liang, Jim Davis
conference: "Arxiv"
year: 2025
bibkey: liang2025making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02248"}
  - {name: "Code", url: "https://github.com/ltong1130ztr/HAPrompts}{https://github.com/ltong1130ztr/HAPrompts"}
tags: ['Prompting', 'RAG', 'Has Code']
---
Recent studies are leveraging advancements in large language models (LLMs)
trained on extensive internet-crawled text data to generate textual
descriptions of downstream classes in CLIP-based zero-shot image
classification. While most of these approaches aim at improving accuracy, our
work focuses on ``making better mistakes", of which the mistakes' severities
are derived from the given label hierarchy of downstream tasks. Since CLIP's
image encoder is trained with language supervising signals, it implicitly
captures the hierarchical semantic relationships between different classes.
This motivates our goal of making better mistakes in zero-shot classification,
a task for which CLIP is naturally well-suited. Our approach (HAPrompts)
queries the language model to produce textual representations for given classes
as zero-shot classifiers of CLIP to perform image classification on downstream
tasks. To our knowledge, this is the first work to introduce making better
mistakes in CLIP-based zero-shot classification. Our approach outperforms the
related methods in a holistic comparison across five datasets of varying scales
with label hierarchies of different heights in our experiments. Our code and
LLM-generated image prompts:
\href\{https://github.com/ltong1130ztr/HAPrompts\}\{https://github.com/ltong1130ztr/HAPrompts\}.
