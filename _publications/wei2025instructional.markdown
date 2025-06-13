---
layout: publication
title: 'Instructionbench: An Instructional Video Understanding Benchmark'
authors: Haiwan Wei, Yitian Yuan, Xiaohan Lan, Wei Ke, Lin Ma
conference: "Arxiv"
year: 2025
bibkey: wei2025instructional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05040"}
tags: ['Model Architecture', 'GPT', 'Tools', 'Reinforcement Learning']
---
Despite progress in video large language models (Video-LLMs), research on
instructional video understanding, crucial for enhancing access to
instructional content, remains insufficient. To address this, we introduce
InstructionBench, an Instructional video understanding Benchmark, which
challenges models' advanced temporal reasoning within instructional videos
characterized by their strict step-by-step flow. Employing GPT-4, we formulate
Q\&A pairs in open-ended and multiple-choice formats to assess both
Coarse-Grained event-level and Fine-Grained object-level reasoning. Our
filtering strategies exclude questions answerable purely by common-sense
knowledge, focusing on visual perception and analysis when evaluating Video-LLM
models. The benchmark finally contains 5k questions across over 700 videos. We
evaluate the latest Video-LLMs on our InstructionBench, finding that
closed-source models outperform open-source ones. However, even the best model,
GPT-4o, achieves only 53.42% accuracy, indicating significant gaps in temporal
reasoning. To advance the field, we also develop a comprehensive instructional
video dataset with over 19k Q\&A pairs from nearly 2.5k videos, using an
automated data generation framework, thereby enriching the community's research
resources.
