---
layout: publication
title: 'Tabgen-icl: Residual-aware In-context Example Selection For Tabular Data Generation'
authors: Liancheng Fang, Aiwei Liu, Hengrui Zhang, Henry Peng Zou, Weizhi Zhang, Philip S. Yu
conference: "Arxiv"
year: 2025
bibkey: fang2025tabgen
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16414"}
  - {name: "Code", url: "https://github.com/fangliancheng/TabGEN-ICL}{link"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting', 'In-Context Learning']
---
Large Language models (LLMs) have achieved encouraging results in tabular
data generation. However, existing approaches require fine-tuning, which is
computationally expensive. This paper explores an alternative: prompting a
fixed LLM with in-context examples. We observe that using randomly selected
in-context examples hampers the LLM's performance, resulting in sub-optimal
generation quality. To address this, we propose a novel in-context learning
framework: TabGen-ICL, to enhance the in-context learning ability of LLMs for
tabular data generation. TabGen-ICL operates iteratively, retrieving a subset
of real samples that represent the residual between currently generated samples
and true data distributions. This approach serves two purposes: locally, it
provides more effective in-context learning examples for the LLM in each
iteration; globally, it progressively narrows the gap between generated and
real data. Extensive experiments on five real-world tabular datasets
demonstrate that TabGen-ICL significantly outperforms the random selection
strategy. Specifically, it reduces the error rate by a margin of \\(3.5%-42.2%\\)
on fidelity metrics. We demonstrate for the first time that prompting a fixed
LLM can yield high-quality synthetic tabular data. The code is provided in the
\href\{https://github.com/fangliancheng/TabGEN-ICL\}\{link\}.
