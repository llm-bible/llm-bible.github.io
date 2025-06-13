---
layout: publication
title: 'SUV: Scalable Large Language Model Copyright Compliance With Regularized Selective Unlearning'
authors: Tianyang Xu, Xiaoze Liu, Feijie Wu, Xiaoqian Wang, Jing Gao
conference: "Arxiv"
year: 2025
bibkey: xu2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22948"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning', 'Prompting']
---
Large Language Models (LLMs) have transformed natural language processing by
learning from massive datasets, yet this rapid progress has also drawn legal
scrutiny, as the ability to unintentionally generate copyrighted content has
already prompted several prominent lawsuits. In this work, we introduce SUV
(Selective Unlearning for Verbatim data), a selective unlearning framework
designed to prevent LLM from memorizing copyrighted content while preserving
its overall utility. In detail, the proposed method constructs a dataset that
captures instances of copyrighted infringement cases by the targeted LLM. With
the dataset, we unlearn the content from the LLM by means of Direct Preference
Optimization (DPO), which replaces the verbatim copyrighted content with
plausible and coherent alternatives. Since DPO may hinder the LLM's performance
in other unrelated tasks, we integrate gradient projection and Fisher
information regularization to mitigate the degradation. We validate our
approach using a large-scale dataset of 500 famous books (predominantly
copyrighted works) and demonstrate that SUV significantly reduces verbatim
memorization with negligible impact on the performance on unrelated tasks.
Extensive experiments on both our dataset and public benchmarks confirm the
scalability and efficacy of our approach, offering a promising solution for
mitigating copyright risks in real-world LLM applications.
