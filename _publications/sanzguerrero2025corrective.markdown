---
layout: publication
title: 'Corrective In-context Learning: Evaluating Self-correction In Large Language Models'
authors: Mario Sanz-guerrero, Katharina Von Der Wense
conference: "Arxiv"
year: 2025
bibkey: sanzguerrero2025corrective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16022"}
tags: ['Few-Shot', 'Prompting', 'In-Context Learning', 'Merging']
---
In-context learning (ICL) has transformed the use of large language models
(LLMs) for NLP tasks, enabling few-shot learning by conditioning on labeled
examples without finetuning. Despite its effectiveness, ICL is prone to errors,
especially for challenging examples. With the goal of improving the performance
of ICL, we propose corrective in-context learning (CICL), an approach that
incorporates a model's incorrect predictions alongside ground truth corrections
into the prompt, aiming to enhance classification accuracy through
self-correction. However, contrary to our hypothesis, extensive experiments on
text classification tasks demonstrate that CICL consistently underperforms
standard ICL, with performance degrading as the proportion of corrections in
the prompt increases. Our findings indicate that CICL introduces confusion by
disrupting the model's task understanding, rather than refining its
predictions. Additionally, we observe that presenting harder examples in
standard ICL does not improve performance, suggesting that example difficulty
alone may not be a reliable criterion for effective selection. By presenting
these negative results, we provide important insights into the limitations of
self-corrective mechanisms in LLMs and offer directions for future research.
