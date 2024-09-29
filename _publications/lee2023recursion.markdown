---
layout: publication
title: Recursion Of Thought A Divide45;and45;conquer Approach To Multi45;context Reasoning With Language Models
authors: Soochan Lee, Gunhee Kim
conference: "Arxiv"
year: 2023
bibkey: lee2023recursion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2306.06891v1"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
Generating intermediate steps or Chain of Thought (CoT) is an effective way to significantly improve language models (LM) multi45;step reasoning capability. However the CoT lengths can grow rapidly with the problem complexity easily exceeding the maximum context size. Instead of increasing the context limit which has already been heavily investigated we explore an orthogonal direction making LMs divide a problem into multiple contexts. We propose a new inference framework called Recursion of Thought (RoT) which introduces several special tokens that the models can output to trigger context45;related operations. Extensive experiments with multiple architectures including GPT45;3 show that RoT dramatically improves LMs inference capability to solve problems whose solution consists of hundreds of thousands of tokens.
