---
layout: publication
title: 'Elephants Never Forget: Memorization And Learning Of Tabular Data In Large Language Models'
authors: Bordt Sebastian, Nori Harsha, Rodrigues Vanessa, Nushi Besmira, Caruana Rich
conference: "Arxiv"
year: 2024
bibkey: bordt2024elephants
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06209"}
  - {name: "Code", url: "https://github.com/interpretml/LLM-Tabular-Memorization-Checker"}
tags: ['Efficiency And Optimization', 'Few Shot', 'Has Code', 'Reinforcement Learning', 'Training Techniques', 'Uncategorized']
---
While many have shown how Large Language Models (LLMs) can be applied to a
diverse set of tasks, the critical issues of data contamination and
memorization are often glossed over. In this work, we address this concern for
tabular data. Specifically, we introduce a variety of different techniques to
assess whether a language model has seen a tabular dataset during training.
This investigation reveals that LLMs have memorized many popular tabular
datasets verbatim. We then compare the few-shot learning performance of LLMs on
datasets that were seen during training to the performance on datasets released
after training. We find that LLMs perform better on datasets seen during
training, indicating that memorization leads to overfitting. At the same time,
LLMs show non-trivial performance on novel datasets and are surprisingly robust
to data transformations. We then investigate the in-context statistical
learning abilities of LLMs. While LLMs are significantly better than random at
solving statistical classification problems, the sample efficiency of few-shot
learning lags behind traditional statistical learning algorithms, especially as
the dimension of the problem increases. This suggests that much of the observed
few-shot performance on novel real-world datasets is due to the LLM's world
knowledge. Overall, our results highlight the importance of testing whether an
LLM has seen an evaluation dataset during pre-training. We release the
https://github.com/interpretml/LLM-Tabular-Memorization-Checker Python package
to test LLMs for memorization of tabular datasets.
