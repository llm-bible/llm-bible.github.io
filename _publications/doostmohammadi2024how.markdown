---
layout: publication
title: How Reliable Are Automatic Evaluation Methods For Instruction45;tuned Llms
authors: Doostmohammadi Ehsan, Holmström Oskar, Kuhlmann Marco
conference: "Arxiv"
year: 2024
bibkey: doostmohammadi2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10770"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Work on instruction45;tuned Large Language Models (LLMs) has used automatic methods based on text overlap and LLM judgments as cost45;effective alternatives to human evaluation. In this paper we perform a meta45;evaluation of such methods and assess their reliability across a broad range of tasks. We observe that while automatic evaluation methods can approximate human ratings under specific conditions their validity is highly context45;dependent. Specifically the simple ROUGE45;L metric correlates well with human ratings for short45;answer English tasks but is unreliable in free45;form generation tasks and cross45;lingual transfer. The effectiveness of the more advanced method of using GPT45;4 as a judge diminishes significantly if reference answers are not included in the prompt which is the scenario where this method has the potential to provide the most value compared to other metrics. Our findings enhance the understanding of how automatic methods should be applied and interpreted when developing and evaluating instruction45;tuned LLMs.
