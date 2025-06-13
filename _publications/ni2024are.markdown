---
layout: publication
title: 'Are Large Language Models More Honest In Their Probabilistic Or Verbalized Confidence?'
authors: Shiyu Ni, Keping Bi, Lulu Yu, Jiafeng Guo
conference: "Arxiv"
year: 2024
bibkey: ni2024are
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.09773'}
tags: ['Reinforcement Learning']
---
Large language models (LLMs) have been found to produce hallucinations when
the question exceeds their internal knowledge boundaries. A reliable model
should have a clear perception of its knowledge boundaries, providing correct
answers within its scope and refusing to answer when it lacks knowledge.
Existing research on LLMs' perception of their knowledge boundaries typically
uses either the probability of the generated tokens or the verbalized
confidence as the model's confidence in its response. However, these studies
overlook the differences and connections between the two. In this paper, we
conduct a comprehensive analysis and comparison of LLMs' probabilistic
perception and verbalized perception of their factual knowledge boundaries.
First, we investigate the pros and cons of these two perceptions. Then, we
study how they change under questions of varying frequencies. Finally, we
measure the correlation between LLMs' probabilistic confidence and verbalized
confidence. Experimental results show that 1) LLMs' probabilistic perception is
generally more accurate than verbalized perception but requires an in-domain
validation set to adjust the confidence threshold. 2) Both perceptions perform
better on less frequent questions. 3) It is challenging for LLMs to accurately
express their internal confidence in natural language.
