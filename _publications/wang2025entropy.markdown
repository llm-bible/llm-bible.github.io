---
layout: publication
title: 'Llm\(\times\)mapreduce-v2: Entropy-driven Convolutional Test-time Scaling For Generating Long-form Articles From Extremely Long Resources'
authors: Haoyu Wang, Yujia Fu, Zhu Zhang, Shuo Wang, Zirui Ren, Xiaorong Wang, Zhili Li, Chaoqun He, Bo An, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: wang2025entropy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05732"}
  - {name: "Code", url: "https://github.com/thunlp/LLMxMapReduce"}
tags: ['Survey Paper', 'Applications', 'Model Architecture', 'Attention Mechanism', 'Has Code']
---
Long-form generation is crucial for a wide range of practical applications,
typically categorized into short-to-long and long-to-long generation. While
short-to-long generations have received considerable attention, generating long
texts from extremely long resources remains relatively underexplored. The
primary challenge in long-to-long generation lies in effectively integrating
and analyzing relevant information from extensive inputs, which remains
difficult for current large language models (LLMs). In this paper, we propose
LLM\\(\times\\)MapReduce-V2, a novel test-time scaling strategy designed to enhance
the ability of LLMs to process extremely long inputs. Drawing inspiration from
convolutional neural networks, which iteratively integrate local features into
higher-level global representations, LLM\\(\times\\)MapReduce-V2 utilizes stacked
convolutional scaling layers to progressively expand the understanding of input
materials. Both quantitative and qualitative experimental results demonstrate
that our approach substantially enhances the ability of LLMs to process long
inputs and generate coherent, informative long-form articles, outperforming
several representative baselines. Both LLM\\(\times\\)MapReduce-V2 and SurveyEval
are publicly available at https://github.com/thunlp/LLMxMapReduce .
