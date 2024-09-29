---
layout: publication
title: RES-Q Evaluating Code-editing Large Language Model Systems At The Repository Scale
authors: Labash Beck, Rosedale August, Reents Alex, Negritto Lucas, Wiel Colin
conference: "Arxiv"
year: 2024
bibkey: labash2024res
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16801"}
  - {name: "Code", url: "https://github.com/Qurrent-AI/RES-Q"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools']
---
The instruction-following ability of Large Language Models (LLMs) has cultivated a class of LLM-based systems capable of approaching complex tasks such as making edits to large code repositories. Due to the high sensitivity and unpredictability of LLM behavior in response to changes in prompting robust evaluation tools are needed to drive future iteration of these systems. We propose RES-Q a natural language instruction-based benchmark for evaluating (textbfR)epository (textbfE)diting (textbfS)ystems which consists of 100 handcrafted repository editing tasks derived from real GitHub commits. Given an edit instruction and a code repository RES-Q evaluates an LLM systems ability to interpret the instruction navigate the repository to gather relevant information and construct an appropriate edit that satisfies the specified criteria. We argue that evaluating LLMs in this way addresses issues with traditional benchmarks and provides a more holistic assessment of a models abilities. We evaluate various state-of-the-art LLMs as language agents in a repository-editing system built on Qurrent OS our language agent development software. Despite their 137; pass35;64;1 performance difference on HumanEval we find Claude Sonnet 3.5 outperforms GPT-4o by 1237; pass35;64;1 on RES-Q indicating RES-Qs capacity to differentiate model capability as traditional benchmarks approach saturation. We further investigate token efficiency performance relationships with existing benchmarks and interesting disparities between closed and open-source LLMs. Code and dataset are available at https://github.com/Qurrent-AI/RES-Q.
