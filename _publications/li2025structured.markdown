---
layout: publication
title: 'Structflowbench: A Structured Flow Benchmark For Multi-turn Instruction Following'
authors: Jinnan Li, Jinzhe Li, Yue Wang, Yi Chang, Yuan Wu
conference: "Arxiv"
year: 2025
bibkey: li2025structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14494"}
  - {name: "Code", url: "https://github.com/MLGroupJLU/StructFlowBench"}
tags: ['Applications', 'Has Code', 'Tools', 'Reinforcement Learning']
---
Multi-turn instruction following capability constitutes a core competency of large language models (LLMs) in real-world applications. Existing evaluation benchmarks predominantly focus on fine-grained constraint satisfaction and domain-specific capability assessment, yet overlook the crucial structural dependencies between dialogue turns that distinguish multi-turn from single-turn interactions. These structural dependencies not only reflect user intent but also establish an essential second dimension for the instruction following evaluation beyond constraint satisfaction. To address this gap, we propose StructFlowBench, a multi-turn instruction following benchmark with structural flow modeling. The benchmark defines an innovative structural flow framework with six fundamental inter-turn relationships. These relationships introduce novel structural constraints for model evaluation and also serve as generation parameters for creating customized dialogue flows tailored to specific scenarios. Adopting established LLM-based automatic evaluation methodologies, we conduct systematic evaluations of 13 leading open-source and closed-source LLMs. Experimental results reveal significant deficiencies in current models' comprehension of multi-turn dialogue structures. The code is available at https://github.com/MLGroupJLU/StructFlowBench.
