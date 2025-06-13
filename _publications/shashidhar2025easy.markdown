---
layout: publication
title: 'Yourbench: Easy Custom Evaluation Sets For Everyone'
authors: Sumuk Shashidhar, Clémentine Fourrier, Alina Lozovskia, Thomas Wolf, Gokhan Tur, Dilek Hakkani-tür
conference: "Arxiv"
year: 2025
bibkey: shashidhar2025easy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.01833"}
tags: ['Applications', 'Tools', 'Reinforcement Learning']
---
Evaluating large language models (LLMs) effectively remains a critical
bottleneck, as traditional static benchmarks suffer from saturation and
contamination, while human evaluations are costly and slow. This hinders timely
or domain-specific assessment, crucial for real-world applications. We
introduce YourBench, a novel, open-source framework that addresses these
limitations by enabling dynamic, automated generation of reliable, up-to-date,
and domain-tailored benchmarks cheaply and without manual annotation, directly
from user-provided documents. We demonstrate its efficacy by replicating 7
diverse MMLU subsets using minimal source text, achieving this for under 15 USD
in total inference costs while perfectly preserving the relative model
performance rankings (Spearman Rho = 1) observed on the original benchmark. To
ensure that YourBench generates data grounded in provided input instead of
relying on posterior parametric knowledge in models, we also introduce
Tempora-0325, a novel dataset of over 7K diverse documents, published
exclusively after March 2025. Our comprehensive analysis spans 26 SoTA models
from 7 major families across varying scales (3-671B parameters) to validate the
quality of generated evaluations through rigorous algorithmic checks (e.g.,
citation grounding) and human assessments. We release the YourBench library,
the Tempora-0325 dataset, 150k+ question answer pairs based on Tempora and all
evaluation and inference traces to facilitate reproducible research and empower
the community to generate bespoke benchmarks on demand, fostering more relevant
and trustworthy LLM evaluation.
