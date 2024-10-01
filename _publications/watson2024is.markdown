---
layout: publication
title: 'Is There No Such Thing As A Bad Question? H4R: Hallucibot For Ratiocination, Rewriting, Ranking, And Routing'
authors: Watson William, Cho Nicole, Srishankar Nishan
conference: "Arxiv"
year: 2024
bibkey: watson2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12535"}
tags: ['Agentic', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Hallucination continues to be one of the most critical challenges in the institutional adoption journey of Large Language Models (LLMs). While prior studies have primarily focused on the post-generation analysis and refinement of outputs, this paper centers on the effectiveness of queries in eliciting accurate responses from LLMs. We present HalluciBot, a model that estimates the query's propensity to hallucinate before generation, without invoking any LLMs during inference. HalluciBot can serve as a proxy reward model for query rewriting, offering a general framework to estimate query quality based on accuracy and consensus. In essence, HalluciBot investigates how poorly constructed queries can lead to erroneous outputs - moreover, by employing query rewriting guided by HalluciBot's empirical estimates, we demonstrate that 95.7&#37; output accuracy can be achieved for Multiple Choice questions. The training procedure for HalluciBot consists of perturbing 369,837 queries n times, employing n+1 independent LLM agents, sampling an output from each query, conducting a Multi-Agent Monte Carlo simulation on the sampled outputs, and training an encoder classifier. The idea of perturbation is the outcome of our ablation studies that measures the increase in output diversity (+12.5 agreement spread) by perturbing a query in lexically different but semantically similar ways. Therefore, HalluciBot paves the way to ratiocinate (76.0&#37; test F1 score, 46.6&#37; in saved computation on hallucinatory queries), rewrite (+30.2&#37; positive class transition from hallucinatory to non-hallucinatory), rank (+50.6&#37; positive class transition from hallucinatory to non-hallucinatory), and route queries to effective pipelines.
