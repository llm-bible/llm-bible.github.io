---
layout: publication
title: 'Designprobe: A Graphic Design Benchmark For Multimodal Large Language Models'
authors: Lin Jieru, Huang Danqing, Zhao Tiejun, Zhan Dechen, Lin Chin-yew
conference: "Arxiv"
year: 2024
bibkey: lin2024graphic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14801"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Tools']
---
A well-executed graphic design typically achieves harmony in two levels, from the fine-grained design elements (color, font and layout) to the overall design. This complexity makes the comprehension of graphic design challenging, for it needs the capability to both recognize the design elements and understand the design. With the rapid development of Multimodal Large Language Models (MLLMs), we establish the DesignProbe, a benchmark to investigate the capability of MLLMs in design. Our benchmark includes eight tasks in total, across both the fine-grained element level and the overall design level. At design element level, we consider both the attribute recognition and semantic understanding tasks. At overall design level, we include style and metaphor. 9 MLLMs are tested and we apply GPT-4 as evaluator. Besides, further experiments indicates that refining prompts can enhance the performance of MLLMs. We first rewrite the prompts by different LLMs and found increased performances appear in those who self-refined by their own LLMs. We then add extra task knowledge in two different ways (text descriptions and image examples), finding that adding images boost much more performance over texts.
