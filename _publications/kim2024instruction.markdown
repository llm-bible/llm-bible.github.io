---
layout: publication
title: 'Instatrans: An Instruction-aware Translation Framework For Non-english Instruction Datasets'
authors: Yungi Kim, Chanjun Park
conference: "Arxiv"
year: 2024
bibkey: kim2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01512"}
tags: ['Fine-Tuning', 'Training Techniques', 'Tools', 'Pretraining Methods']
---
It is challenging to generate high-quality instruction datasets for
non-English languages due to tail phenomena, which limit performance on less
frequently observed data. To mitigate this issue, we propose translating
existing high-quality English instruction datasets as a solution, emphasizing
the need for complete and instruction-aware translations to maintain the
inherent attributes of these datasets. We claim that fine-tuning LLMs with
datasets translated in this way can improve their performance in the target
language. To this end, we introduces a new translation framework tailored for
instruction datasets, named InstaTrans (INSTruction-Aware TRANSlation). Through
extensive experiments, we demonstrate the superiority of InstaTrans over other
competitors in terms of completeness and instruction-awareness of translation,
highlighting its potential to broaden the accessibility of LLMs across diverse
languages at a relatively low cost. Furthermore, we have validated that
fine-tuning LLMs with datasets translated by InstaTrans can effectively improve
their performance in the target language.
