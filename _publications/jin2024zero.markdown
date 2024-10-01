---
layout: publication
title: 'Zero-shot Chain-of-thought Reasoning Guided By Evolutionary Algorithms In Large Language Models'
authors: Jin Feihu, Liu Yifan, Tan Ying
conference: "Arxiv"
year: 2024
bibkey: jin2024zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05376"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated remarkable performance across diverse tasks and exhibited impressive reasoning abilities by applying zero-shot Chain-of-Thought (CoT) prompting. However, due to the evolving nature of sentence prefixes during the pre-training phase, existing zero-shot CoT prompting methods that employ identical CoT prompting across all task instances may not be optimal. In this paper, we introduce a novel zero-shot prompting method that leverages evolutionary algorithms to generate diverse promptings for LLMs dynamically. Our approach involves initializing two CoT promptings, performing evolutionary operations based on LLMs to create a varied set, and utilizing the LLMs to select a suitable CoT prompting for a given problem. Additionally, a rewriting operation, guided by the selected CoT prompting, enhances the understanding of the LLMs about the problem. Extensive experiments conducted across ten reasoning datasets demonstrate the superior performance of our proposed method compared to current zero-shot CoT prompting methods on GPT-3.5-turbo and GPT-4. Moreover, in-depth analytical experiments underscore the adaptability and effectiveness of our method in various reasoning tasks.
