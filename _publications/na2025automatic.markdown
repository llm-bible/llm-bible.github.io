---
layout: publication
title: 'Automatic Transmission For LLM Tiers: Optimizing Cost And Accuracy In Large Language Models'
authors: Injae Na, Keonwoong Noh, Woohwan Jung
conference: "Arxiv"
year: 2025
bibkey: na2025automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20921"}
tags: ['Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
LLM providers typically offer multiple LLM tiers, varying in performance and price. As NLP tasks become more complex and modularized, selecting the suitable LLM tier for each subtask is a key challenge to balance between cost and performance. To address the problem, we introduce LLM Automatic Transmission (LLM-AT) framework that automatically selects LLM tiers without training. LLM-AT consists of Starter, Generator, and Judge. The starter selects the initial LLM tier expected to solve the given question, the generator produces a response using the LLM of the selected tier, and the judge evaluates the validity of the response. If the response is invalid, LLM-AT iteratively upgrades to a higher-tier model, generates a new response, and re-evaluates until a valid response is obtained. Additionally, we propose accuracy estimator, which enables the suitable initial LLM tier selection without training. Given an input question, accuracy estimator estimates the expected accuracy of each LLM tier by computing the valid response rate across top-k similar queries from past inference records. Experiments demonstrate that LLM-AT achieves superior performance while reducing costs, making it a practical solution for real-world applications.
