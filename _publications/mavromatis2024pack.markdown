---
layout: publication
title: Pack Of Llms Model Fusion At Test45;time Via Perplexity Optimization
authors: Mavromatis Costas, Karypis Petros, Karypis George
conference: "Arxiv"
year: 2024
bibkey: mavromatis2024pack
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11531"}
tags: ['Efficiency And Optimization', 'Merging', 'Prompting', 'RAG', 'Training Techniques']
---
Fusing knowledge from multiple Large Language Models (LLMs) can combine their diverse strengths to achieve improved performance on a given task. However current fusion approaches either rely on learning45;based fusers that do not generalize to new LLMs or do not take into account how well each LLM understands the input. In this work we study LLM fusion at test45;time which enables leveraging knowledge from arbitrary user45;specified LLMs during inference. We introduce Pack of LLMs (PackLLM) an effective method for test45;time fusion that leverages each LLMs expertise given an input prompt. PackLLM performs model fusion by solving an optimization problem for determining each LLMs importance so that perplexity over the input prompt is minimized. First our simple PackLLM45;sim variant validates that perplexity is a good indicator for measuring each LLMs expertise. Second our PackLLM45;opt variant approximately solves the perplexity minimization problem via a greedy algorithm. The derived importance weights are used to combine the LLMs during inference. We conduct experiments with over 100 total LLMs on a diverse set of tasks. Experimental results show that (i) perplexity is a reliable measure for LLM fusion (ii) PackLLM outperforms test45;time fusion baselines by 1.8937; accuracy points and (iii) PackLLM can leverage new LLMs to improve performance over learning45;based fusion approaches by 3.9245;11.9437; accuracy points.
