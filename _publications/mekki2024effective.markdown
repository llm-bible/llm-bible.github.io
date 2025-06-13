---
layout: publication
title: 'Effective Self-mining Of In-context Examples For Unsupervised Machine Translation With Llms'
authors: Abdellah El Mekki, Muhammad Abdul-mageed
conference: "Arxiv"
year: 2024
bibkey: mekki2024effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11006"}
tags: ['RAG', 'Prompting', 'In-Context Learning', 'Applications']
---
Large Language Models (LLMs) have demonstrated impressive performance on a
wide range of natural language processing (NLP) tasks, primarily through
in-context learning (ICL). In ICL, the LLM is provided with examples that
represent a given task such that it learns to generate answers for test inputs.
However, access to these in-context examples is not guaranteed especially for
low-resource or massively multilingual tasks. In this work, we propose an
unsupervised approach to mine in-context examples for machine translation (MT),
enabling unsupervised MT (UMT) across different languages. Our approach begins
with word-level mining to acquire word translations that are then used to
perform sentence-level mining. As the quality of mined parallel pairs may not
be optimal due to noise or mistakes, we introduce a filtering criterion to
select the optimal in-context examples from a pool of unsupervised parallel
sentences. We evaluate our approach using two multilingual LLMs on 288
directions from the FLORES-200 dataset and analyze the impact of various
linguistic features on performance. Our findings demonstrate the effectiveness
of our unsupervised approach in mining in-context examples for MT, leading to
better or comparable translation performance as translation with regular
in-context samples (extracted from human-annotated data), while also
outperforming the other state-of-the-art UMT methods by an average of \\(7\\) BLEU
points.
