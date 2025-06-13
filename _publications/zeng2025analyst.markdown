---
layout: publication
title: 'An Analyst-inspector Framework For Evaluating Reproducibility Of Llms In Data Science'
authors: Qiuhai Zeng, Claire Jin, Xinyue Wang, Yuhan Zheng, Qunhua Li
conference: "Arxiv"
year: 2025
bibkey: zeng2025analyst
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16395"}
tags: ['Prompting', 'Applications', 'Tools', 'Fine-Tuning']
---
Large Language Models (LLMs) have demonstrated potential for data science
tasks via code generation. However, the exploratory nature of data science,
alongside the stochastic and opaque outputs of LLMs, raise concerns about their
reliability. While prior work focuses on benchmarking LLM accuracy,
reproducibility remains underexplored, despite being critical to establishing
trust in LLM-driven analysis.
  We propose a novel analyst-inspector framework to automatically evaluate and
enforce the reproducibility of LLM-generated data science workflows - the first
rigorous approach to the best of our knowledge. Defining reproducibility as the
sufficiency and completeness of workflows for reproducing functionally
equivalent code, this framework enforces computational reproducibility
principles, ensuring transparent, well-documented LLM workflows while
minimizing reliance on implicit model assumptions.
  Using this framework, we systematically evaluate five state-of-the-art LLMs
on 1,032 data analysis tasks across three diverse benchmark datasets. We also
introduce two novel reproducibility-enhancing prompting strategies. Our results
show that higher reproducibility strongly correlates with improved accuracy and
reproducibility-enhancing prompts are effective, demonstrating structured
prompting's potential to enhance automated data science workflows and enable
transparent, robust AI-driven analysis. Our code is publicly available.
