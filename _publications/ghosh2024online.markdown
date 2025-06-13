---
layout: publication
title: 'AEGIS: Online Adaptive AI Content Safety Moderation With Ensemble Of LLM Experts'
authors: Shaona Ghosh, Prasoon Varshney, Erick Galinkin, Christopher Parisien
conference: "Arxiv"
year: 2024
bibkey: ghosh2024online
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.05993'}
tags: ['Security', 'Responsible AI', 'Tools']
---
As Large Language Models (LLMs) and generative AI become more widespread, the
content safety risks associated with their use also increase. We find a notable
deficiency in high-quality content safety datasets and benchmarks that
comprehensively cover a wide range of critical safety areas. To address this,
we define a broad content safety risk taxonomy, comprising 13 critical risk and
9 sparse risk categories. Additionally, we curate AEGISSAFETYDATASET, a new
dataset of approximately 26, 000 human-LLM interaction instances, complete with
human annotations adhering to the taxonomy. We plan to release this dataset to
the community to further research and to help benchmark LLM models for safety.
To demonstrate the effectiveness of the dataset, we instruction-tune multiple
LLM-based safety models. We show that our models (named AEGISSAFETYEXPERTS),
not only surpass or perform competitively with the state-of-the-art LLM-based
safety models and general purpose LLMs, but also exhibit robustness across
multiple jail-break attack categories. We also show how using
AEGISSAFETYDATASET during the LLM alignment phase does not negatively impact
the performance of the aligned models on MT Bench scores. Furthermore, we
propose AEGIS, a novel application of a no-regret online adaptation framework
with strong theoretical guarantees, to perform content moderation with an
ensemble of LLM content safety experts in deployment
