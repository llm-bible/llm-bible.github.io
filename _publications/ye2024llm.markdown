---
layout: publication
title: 'LOLA: Llm-assisted Online Learning Algorithm For Content Experiments'
authors: Zikun Ye, Hema Yoganarasimhan, Yufeng Zheng
conference: "Arxiv"
year: 2024
bibkey: ye2024llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.02611'}
tags: ['Reinforcement Learning', 'RAG', 'Prompting', 'Tools']
---
Modern media firms require automated and efficient methods to identify
content that is most engaging and appealing to users. Leveraging a large-scale
dataset from Upworthy (a news publisher), which includes 17,681 headline A/B
tests, we first investigate the ability of three pure-LLM approaches to
identify the catchiest headline: prompt-based methods, embedding-based methods,
and fine-tuned open-source LLMs. Prompt-based approaches perform poorly, while
both OpenAI-embedding-based models and the fine-tuned Llama-3-8B achieve
marginally higher accuracy than random predictions. In sum, none of the
pure-LLM-based methods can predict the best-performing headline with high
accuracy. We then introduce the LLM-Assisted Online Learning Algorithm (LOLA),
a novel framework that integrates Large Language Models (LLMs) with adaptive
experimentation to optimize content delivery. LOLA combines the best pure-LLM
approach with the Upper Confidence Bound algorithm to allocate traffic and
maximize clicks adaptively. Our numerical experiments on Upworthy data show
that LOLA outperforms the standard A/B test method (the current status quo at
Upworthy), pure bandit algorithms, and pure-LLM approaches, particularly in
scenarios with limited experimental traffic. Our approach is scalable and
applicable to content experiments across various settings where firms seek to
optimize user engagement, including digital advertising and social media
recommendations.
