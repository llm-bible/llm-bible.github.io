---
layout: publication
title: 'Densing Law Of Llms'
authors: Chaojun Xiao, Jie Cai, Weilin Zhao, Guoyang Zeng, Biyuan Lin, Jie Zhou, Zhi Zheng, Xu Han, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: xiao2024densing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.04315'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Training Techniques', 'Tools']
---
Large Language Models (LLMs) have emerged as a milestone in artificial
intelligence, and their performance can improve as the model size increases.
However, this scaling brings great challenges to training and inference
efficiency, particularly for deploying LLMs in resource-constrained
environments, and the scaling trend is becoming increasingly unsustainable.
This paper introduces the concept of ``\textit\{capacity density\}'' as a new
metric to evaluate the quality of the LLMs across different scales and
describes the trend of LLMs in terms of both effectiveness and efficiency. To
calculate the capacity density of a given target LLM, we first introduce a set
of reference models and develop a scaling law to predict the downstream
performance of these reference models based on their parameter sizes. We then
define the \textit\{effective parameter size\} of the target LLM as the parameter
size required by a reference model to achieve equivalent performance, and
formalize the capacity density as the ratio of the effective parameter size to
the actual parameter size of the target LLM. Capacity density provides a
unified framework for assessing both model effectiveness and efficiency. Our
further analysis of recent open-source base LLMs reveals an empirical law (the
densing law)that the capacity density of LLMs grows exponentially over time.
More specifically, using some widely used benchmarks for evaluation, the
capacity density of LLMs doubles approximately every three months. The law
provides new perspectives to guide future LLM development, emphasizing the
importance of improving capacity density to achieve optimal results with
minimal computational overhead.
