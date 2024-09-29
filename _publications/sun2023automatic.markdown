---
layout: publication
title: Autohint Automatic Prompt Optimization With Hint Generation
authors: Sun Hong, Li Xue, Xu Yinchuan, Homma Youkow, Cao Qi, Wu Min, Jiao Jian, Charles Denis
conference: "Arxiv"
year: 2023
bibkey: sun2023automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.07415"}
tags: ['Efficiency And Optimization', 'Prompting', 'Tools']
---
This paper presents AutoHint a novel framework for automatic prompt engineering and optimization for Large Language Models (LLM). While LLMs have demonstrated remarkable ability in achieving high45;quality annotation in various tasks the key to applying this ability to specific tasks lies in developing high45;quality prompts. Thus we propose a framework to inherit the merits of both in45;context learning and zero45;shot learning by incorporating enriched instructions derived from input45;output demonstrations to optimize original prompt. We refer to the enrichment as the hint and propose a framework to automatically generate the hint from labeled data. More concretely starting from an initial prompt our method first instructs a LLM to deduce new hints for selected samples from incorrect predictions and then summarizes from per45;sample hints and adds the results back to the initial prompt to form a new enriched instruction. The proposed method is evaluated on the BIG45;Bench Instruction Induction dataset for both zero45;shot and few45;short prompts where experiments demonstrate our method is able to significantly boost accuracy for multiple tasks.
