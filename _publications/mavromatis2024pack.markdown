---
layout: publication
title: Pack of LLMs Model Fusion at Test-Time via Perplexity Optimization
authors: Mavromatis Costas, Karypis Petros, Karypis George
conference: "Arxiv"
year: 2024
bibkey: mavromatis2024pack
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11531"}
tags: ['ARXIV', 'Efficiency And Optimization', 'LLM', 'Merging', 'Prompting', 'RAG', 'Training Techniques']
---
Fusing knowledge from multiple Large Language Models (LLMs) can combine their diverse strengths to achieve improved performance on a given task. However current fusion approaches either rely on learning-based fusers that do not generalize to new LLMs or do not take into account how well each LLM understands the input. In this work we study LLM fusion at test-time which enables leveraging knowledge from arbitrary user-specified LLMs during inference. We introduce Pack of LLMs (PackLLM) an effective method for test-time fusion that leverages each LLMs expertise given an input prompt. PackLLM performs model fusion by solving an optimization problem for determining each LLMs importance so that perplexity over the input prompt is minimized. First our simple PackLLM-sim variant validates that perplexity is a good indicator for measuring each LLMs expertise. Second our PackLLM-opt variant approximately solves the perplexity minimization problem via a greedy algorithm. The derived importance weights are used to combine the LLMs during inference. We conduct experiments with over 100 total LLMs on a diverse set of tasks. Experimental results show that (i) perplexity is a reliable measure for LLM fusion (ii) PackLLM outperforms test-time fusion baselines by 1.89 accuracy points and (iii) PackLLM can leverage new LLMs to improve performance over learning-based fusion approaches by 3.92-11.94 accuracy points.
