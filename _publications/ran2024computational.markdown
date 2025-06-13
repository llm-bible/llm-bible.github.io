---
layout: publication
title: 'Alopex: A Computational Framework For Enabling On-device Function Calls With Llms'
authors: Yide Ran, Zhaozhuo Xu, Yuhang Yao, Zijian Hu, Shanshan Han, Han Jin, Alay Dilipbhai Shah, Jipeng Zhang, Dimitris Stripelis, Tong Zhang, Salman Avestimehr, Chaoyang He
conference: "Arxiv"
year: 2024
bibkey: ran2024computational
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.05209'}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
The rapid advancement of Large Language Models (LLMs) has led to their
increased integration into mobile devices for personalized assistance, which
enables LLMs to call external API functions to enhance their performance.
However, challenges such as data scarcity, ineffective question formatting, and
catastrophic forgetting hinder the development of on-device LLM agents. To
tackle these issues, we propose Alopex, a framework that enables precise
on-device function calls using the Fox LLM. Alopex introduces a logic-based
method for generating high-quality training data and a novel
``description-question-output'' format for fine-tuning, reducing risks of
function information leakage. Additionally, a data mixing strategy is used to
mitigate catastrophic forgetting, combining function call data with textbook
datasets to enhance performance in various tasks. Experimental results show
that Alopex improves function call accuracy and significantly reduces
catastrophic forgetting, providing a robust solution for integrating function
call capabilities into LLMs without manual intervention.
