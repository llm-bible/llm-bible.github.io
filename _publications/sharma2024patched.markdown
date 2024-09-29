---
layout: publication
title: Patched MOA optimizing inference for diverse software development tasks
authors: Sharma Asankhaya
conference: "Arxiv"
year: 2024
bibkey: sharma2024patched
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18521"}
  - {name: "Code", url: "https://github.com/codelion/optillm"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
This paper introduces Patched MOA (Mixture of Agents) an inference optimization technique that significantly enhances the performance of large language models (LLMs) across diverse software development tasks. We evaluate three inference optimization algorithms - Best of N Mixture of Agents and Monte Carlo Tree Search and demonstrate that Patched MOA can boost the performance of smaller models to surpass that of larger more expensive models. Notably our approach improves the gpt-4o-mini models performance on the Arena-Hard-Auto benchmark by 15.52 outperforming gpt-4-turbo at a fraction of the cost. We also apply Patched MOA to various software development workflows showing consistent improvements in task completion rates. Our method is model-agnostic transparent to end-users and can be easily integrated into existing LLM pipelines. This work contributes to the growing field of LLM optimization offering a cost-effective solution for enhancing model performance without the need for fine-tuning or larger models. Our implementation is open-source and available at https://github.com/codelion/optillm.
