---
layout: publication
title: 'Lugha-llama: Adapting Large Language Models For African Languages'
authors: Happy Buzaaba, Alexander Wettig, David Ifeoluwa Adelani, Christiane Fellbaum
conference: "Arxiv"
year: 2025
bibkey: buzaaba2025lugha
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06536"}
tags: ['RAG', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
Large language models (LLMs) have achieved impressive results in a wide range
of natural language applications. However, they often struggle to recognize
low-resource languages, in particular African languages, which are not well
represented in large training corpora. In this paper, we consider how to adapt
LLMs to low-resource African languages. We find that combining curated data
from African languages with high-quality English educational texts results in a
training mix that substantially improves the model's performance on these
languages. On the challenging IrokoBench dataset, our models consistently
achieve the best performance amongst similarly sized baselines, particularly on
knowledge-intensive multiple-choice questions (AfriMMLU). Additionally, on the
cross-lingual question answering benchmark AfriQA, our models outperform the
base model by over 10%. To better understand the role of English data during
training, we translate a subset of 200M tokens into Swahili language and
perform an analysis which reveals that the content of these data is primarily
responsible for the strong performance. We release our models and data to
encourage future research on African languages.
