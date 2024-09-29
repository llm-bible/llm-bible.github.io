---
layout: publication
title: How Predictable Are Large Language Model Capabilities A Case Study On Big45;bench
authors: Ye Qinyuan, Fu Harvey Yiyun, Ren Xiang, Jia Robin
conference: "Arxiv"
year: 2023
bibkey: ye2023how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14947"}
tags: ['Ethics And Bias']
---
We investigate the predictability of large language model (LLM) capabilities given records of past experiments using different model families numbers of parameters tasks and numbers of in45;context examples can we accurately predict LLM performance on new experiment configurations Answering this question has practical implications for LLM users (e.g. deciding which models to try) developers (e.g. prioritizing evaluation on representative tasks) and the research community (e.g. identifying hard45;to45;predict capabilities that warrant further investigation). We study the performance prediction problem on experiment records from BIG45;bench. On a random train45;test split an MLP45;based predictor achieves an R^2 score greater than 9537; indicating the presence of learnable patterns within the experiment records. We then formulate the problem of searching for small45;bench an informative subset of BIG45;bench tasks from which the performance on the full set can be maximally recovered. We find a subset as informative as BIG45;bench Hard for evaluating new model families while being 3× smaller. Additionally we find competitive subsets by clustering task representations learned by our MLP45;based predictor and selecting tasks close to cluster centroids highlighting the importance of task diversity in constructing small45;bench.
