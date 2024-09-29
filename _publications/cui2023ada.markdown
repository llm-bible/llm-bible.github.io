---
layout: publication
title: "Ada-instruct: Adapting Instruction Generators For Complex Reasoning"
authors: Cui Wanyun, Wang Qianle
conference: "Arxiv"
year: 2023
bibkey: cui2023ada
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04484"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Generating diverse and sophisticated instructions for downstream tasks by Large Language Models (LLMs) is pivotal for advancing the effect. Current approaches leverage closed-source LLMs employing in-context prompting for instruction generation. However in this paper we found that in-context prompting cannot generate complex instructions with length (ge) 100 for tasks like code completion. To solve this problem we introduce Ada-Instruct an adaptive instruction generator developed by fine-tuning open-source LLMs. Our pivotal finding illustrates that fine-tuning open-source LLMs with a mere ten samples generates long instructions that maintain distributional consistency for complex reasoning tasks. We empirically validated Ada-Instructs efficacy across different applications including code completion mathematical reasoning and commonsense reasoning. The results underscore Ada-Instructs superiority evidencing its improvements over its base models current self-instruct methods and other state-of-the-art models.
