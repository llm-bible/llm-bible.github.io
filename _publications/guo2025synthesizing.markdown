---
layout: publication
title: 'Sqlforge: Synthesizing Reliable And Diverse Data To Enhance Text-to-sql Reasoning In Llms'
authors: Yu Guo, Dong Jin, Shenghao Ye, Shuangwu Chen, Jian Yang, Xiaobin Tan
conference: "Arxiv"
year: 2025
bibkey: guo2025synthesizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13725"}
tags: ['Model Architecture', 'Fine-Tuning']
---
Large Language models (LLMs) have demonstrated significant potential in text-to-SQL reasoning tasks, yet a substantial performance gap persists between existing open-source models and their closed-source counterparts. In this paper, we introduce SQLForge, a novel approach for synthesizing reliable and diverse data to enhance text-to-SQL reasoning in LLMs. We improve data reliability through SQL syntax constraints and SQL-to-question reverse translation, ensuring data logic at both structural and semantic levels. We also propose an SQL template enrichment and iterative data domain exploration mechanism to boost data diversity. Building on the augmented data, we fine-tune a variety of open-source models with different architectures and parameter sizes, resulting in a family of models termed SQLForge-LM. SQLForge-LM achieves the state-of-the-art performance on the widely recognized Spider and BIRD benchmarks among the open-source models. Specifically, SQLForge-LM achieves EX accuracy of 85.7% on Spider Dev and 59.8% on BIRD Dev, significantly narrowing the performance gap with closed-source methods.
