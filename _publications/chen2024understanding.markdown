---
layout: publication
title: 'Understanding When Tree Of Thoughts Succeeds: Larger Models Excel In Generation, Not Discrimination'
authors: Qiqi Chen, Xinpeng Wang, Philipp Mondorf, Michael A. Hedderich, Barbara Plank
conference: "Arxiv"
year: 2024
bibkey: chen2024understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17820'}
tags: ['Prompting']
---
Tree of Thoughts (ToT) is a reasoning strategy for Large Language Models
(LLMs) that employs a generator to suggest reasoning steps and a discriminator
to decide which steps to implement. ToT demonstrates strong performance on
reasoning tasks, often surpassing simple methods such as Input-Output (IO)
prompting and Chain-of-Thought (CoT) reasoning. However, ToT does not
consistently outperform such simpler methods across all models, leaving large
knowledge gaps on the conditions under which ToT is most beneficial. In this
paper, we analyze the roles of the generator and discriminator separately to
better understand the conditions when ToT is beneficial. We find that the
generator plays a more critical role than the discriminator in driving the
success of ToT. Scaling the generator leads to notable improvements in ToT
performance, even when using a smaller model as the discriminator, whereas
scaling the discriminator with a fixed generator yields only marginal gains.
Our results show that models across different scales exhibit comparable
discrimination capabilities, yet differ significantly in their generative
performance for ToT.
