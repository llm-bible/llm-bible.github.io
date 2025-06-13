---
layout: publication
title: 'Recurrent Alignment With Hard Attention For Hierarchical Text Rating'
authors: Chenxi Lin, Jiayu Ren, Guoxiu He, Zhuoren Jiang, Haiyan Yu, Xiaomin Zhu
conference: "Arxiv"
year: 2024
bibkey: lin2024recurrent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08874"}
  - {name: "Code", url: "https://github.com/ECNU-Text-Computing/Markov-LLM"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'Has Code', 'Prompting', 'Attention Mechanism']
---
While large language models (LLMs) excel at understanding and generating
plain text, they are not tailored to handle hierarchical text structures or
directly predict task-specific properties such as text rating. In fact,
selectively and repeatedly grasping the hierarchical structure of large-scale
text is pivotal for deciphering its essence. To this end, we propose a novel
framework for hierarchical text rating utilizing LLMs, which incorporates
Recurrent Alignment with Hard Attention (RAHA). Particularly, hard attention
mechanism prompts a frozen LLM to selectively focus on pertinent leaf texts
associated with the root text and generate symbolic representations of their
relationships. Inspired by the gradual stabilization of the Markov Chain,
recurrent alignment strategy involves feeding predicted ratings iteratively
back into the prompts of another trainable LLM, aligning it to progressively
approximate the desired target. Experimental results demonstrate that RAHA
outperforms existing state-of-the-art methods on three hierarchical text rating
datasets. Theoretical and empirical analysis confirms RAHA's ability to
gradually converge towards the underlying target through multiple inferences.
Additional experiments on plain text rating datasets verify the effectiveness
of this Markov-like alignment. Our data and code can be available in
https://github.com/ECNU-Text-Computing/Markov-LLM.
