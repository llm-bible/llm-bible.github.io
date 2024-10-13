---
layout: publication
title: 'Code Prompting: A Neural Symbolic Method For Complex Reasoning In Large Language Models'
authors: Hu Yi, Yang Haotong, Lin Zhouchen, Zhang Muhan
conference: "Arxiv"
year: 2023
bibkey: hu2023code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18507"}
tags: ['Few Shot', 'Merging', 'Prompting', 'Uncategorized']
---
Large language models (LLMs) have scaled up to unlock a wide range of complex
reasoning tasks with the aid of various prompting methods. However, current
prompting methods generate natural language intermediate steps to help
reasoning, which can cause imperfect task reduction and confusion. To mitigate
such limitations, we explore code prompting, a neural symbolic prompting method
with both zero-shot and few-shot versions which triggers code as intermediate
steps. We conduct experiments on 7 widely-used benchmarks involving symbolic
reasoning and arithmetic reasoning. Code prompting generally outperforms
chain-of-thought (CoT) prompting. To further understand the performance and
limitations of code prompting, we perform extensive ablation studies and error
analyses, and identify several exclusive advantages of using symbolic
promptings compared to natural language. We also consider the ensemble of code
prompting and CoT prompting to combine the strengths of both. Finally, we show
through experiments how code annotations and their locations affect code
prompting.
