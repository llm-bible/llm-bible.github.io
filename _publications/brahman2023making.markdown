---
layout: publication
title: 'Plasma: Making Small Language Models Better Procedural Knowledge Models For (counterfactual) Planning'
authors: Faeze Brahman, Chandra Bhagavatula, Valentina Pyatkin, Jena D. Hwang, Xiang Lorraine Li, Hirona J. Arai, Soumya Sanyal, Keisuke Sakaguchi, Xiang Ren, Yejin Choi
conference: "Arxiv"
year: 2023
bibkey: brahman2023making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19472"}
tags: ['Tools', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Distillation']
---
Procedural planning, which entails decomposing a high-level goal into a
sequence of temporally ordered steps, is an important yet intricate task for
machines. It involves integrating common-sense knowledge to reason about
complex and often contextualized situations, e.g. ``scheduling a doctor's
appointment without a phone''. While current approaches show encouraging
results using large language models (LLMs), they are hindered by drawbacks such
as costly API calls and reproducibility issues. In this paper, we advocate
planning using smaller language models. We present PlaSma, a novel two-pronged
approach to endow small language models with procedural knowledge and
(constrained) language planning capabilities. More concretely, we develop
symbolic procedural knowledge distillation to enhance the commonsense knowledge
in small language models and an inference-time algorithm to facilitate more
structured and accurate reasoning. In addition, we introduce a new related
task, Replanning, that requires a revision of a plan to cope with a constrained
situation. In both the planning and replanning settings, we show that
orders-of-magnitude smaller models (770M-11B parameters) can compete and often
surpass their larger teacher models' capabilities. Finally, we showcase
successful application of PlaSma in an embodied environment, VirtualHome.
