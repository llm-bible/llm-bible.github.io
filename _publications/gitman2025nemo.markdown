---
layout: publication
title: 'Nemo-inspector: A Visualization Tool For LLM Generation Analysis'
authors: Daria Gitman, Igor Gitman, Evelina Bakhturina
conference: "Arxiv"
year: 2025
bibkey: gitman2025nemo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00903"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning']
---
Adapting Large Language Models (LLMs) to novel tasks and enhancing their
overall capabilities often requires large, high-quality training datasets.
Synthetic data, generated at scale, serves a valuable alternative when
real-world data is scarce or difficult to obtain. However, ensuring the quality
of synthetic datasets is challenging, as developers must manually inspect and
refine numerous samples to identify errors and areas for improvement. This
process is time-consuming and requires specialized tools. We introduce
NeMo-Inspector, an open-source tool designed to simplify the analysis of
synthetic datasets with integrated inference capabilities. We demonstrate its
effectiveness through two real-world cases. Analysis and cleaning of the
synthetically generated GSM-Plus dataset with NeMo-Inspector led to a
significant decrease in low-quality samples from 46.99% to 19.51%. The tool
also helped identify and correct generation errors in OpenMath models,
improving accuracy by 1.92% on the MATH dataset and by 4.17% on the GSM8K
dataset for a Meta-Llama-3-8B model fine-tuned on synthetic data generated from
Nemotron-4-340B.
