---
layout: publication
title: How Reliable Are Automatic Evaluation Methods for Instruction-Tuned LLMs
authors: Doostmohammadi Ehsan, Holmström Oskar, Kuhlmann Marco
conference: "Arxiv"
year: 2024
bibkey: doostmohammadi2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10770"}
tags: ['ARXIV', 'Ethics And Bias', 'GPT', 'LLM', 'Model Architecture', 'Reinforcement Learning']
---
Work on instruction-tuned Large Language Models (LLMs) has used automatic methods based on text overlap and LLM judgments as cost-effective alternatives to human evaluation. In this paper we perform a meta-evaluation of such methods and assess their reliability across a broad range of tasks. We observe that while automatic evaluation methods can approximate human ratings under specific conditions their validity is highly context-dependent. Specifically the simple ROUGE-L metric correlates well with human ratings for short-answer English tasks but is unreliable in free-form generation tasks and cross-lingual transfer. The effectiveness of the more advanced method of using GPT-4 as a judge diminishes significantly if reference answers are not included in the prompt which is the scenario where this method has the potential to provide the most value compared to other metrics. Our findings enhance the understanding of how automatic methods should be applied and interpreted when developing and evaluating instruction-tuned LLMs.
