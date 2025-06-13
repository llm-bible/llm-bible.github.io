---
layout: publication
title: 'Why Is Prompting Hard? Understanding Prompts On Binary Sequence Predictors'
authors: Li Kevin Wenliang, Anian Ruoss, Jordi Grau-moya, Marcus Hutter, Tim Genewein
conference: "Arxiv"
year: 2025
bibkey: wenliang2025why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.10760"}
tags: ['Prompting', 'Pretraining Methods', 'Training Techniques']
---
Large language models (LLMs) can be prompted to do many tasks, but finding
good prompts is not always easy, nor is understanding some performant prompts.
We explore these issues by viewing prompting as conditioning a near-optimal
sequence predictor (LLM) pretrained on diverse data sources. Through numerous
prompt search experiments, we show that the unintuitive patterns in optimal
prompts can be better understood given the pretraining distribution, which is
often unavailable in practice. Moreover, even using exhaustive search, reliably
identifying optimal prompts from practical neural predictors can be difficult.
Further, we demonstrate that common prompting methods, such as using intuitive
prompts or samples from the targeted task, are in fact suboptimal. Thus, this
work takes an initial step towards understanding the difficulties in finding
and understanding optimal prompts from a statistical and empirical perspective.
