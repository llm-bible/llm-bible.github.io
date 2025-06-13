---
layout: publication
title: 'Improving Mathematical Reasoning Capabilities Of Small Language Models Via Feedback-driven Distillation'
authors: Xunyu Zhu, Jian Li, Can Ma, Weiping Wang
conference: "Arxiv"
year: 2024
bibkey: zhu2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.14698'}
tags: ['Prompting', 'Efficiency and Optimization', 'Distillation', 'Tools']
---
Large Language Models (LLMs) demonstrate exceptional reasoning capabilities,
often achieving state-of-the-art performance in various tasks. However, their
substantial computational and memory demands, due to billions of parameters,
hinder deployment in resource-constrained environments. A promising solution is
knowledge distillation, where LLMs transfer reasoning capabilities to Small
Language Models (SLMs, \\(\le\\) 1B parameters), enabling wider deployment on
low-resource devices. Existing methods primarily focus on generating
high-quality reasoning rationales for distillation datasets but often neglect
the critical role of data quantity and quality. To address these challenges, we
propose a Feedback-Driven Distillation (FDD) framework to enhance SLMs'
mathematical reasoning capabilities. In the initialization stage, a
distillation dataset is constructed by prompting LLMs to pair mathematical
problems with corresponding reasoning rationales. We classify problems into
easy and hard categories based on SLM performance. For easy problems, LLMs
generate more complex variations, while for hard problems, new questions of
similar complexity are synthesized. In addition, we propose a multi-round
distillation paradigm to iteratively enrich the distillation datasets, thereby
progressively improving the mathematical reasoning abilities of SLMs.
Experimental results demonstrate that our method can make SLMs achieve SOTA
mathematical reasoning performance.
