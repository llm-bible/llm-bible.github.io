---
layout: publication
title: 'Turtlebench: Evaluating Top Language Models Via Real-world Yes/no Puzzles'
authors: Qingchen Yu, Shichao Song, Ke Fang, Yunfeng Shi, Zifan Zheng, Hanyu Wang, Simin Niu, Zhiyu Li
conference: "Arxiv"
year: 2024
bibkey: yu2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.05262'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'Tools']
---
As the application of Large Language Models (LLMs) expands, the demand for
reliable evaluations increases. Existing LLM evaluation benchmarks primarily
rely on static datasets, making it challenging to assess model performance in
dynamic interactions with users. Moreover, these benchmarks often depend on
specific background knowledge, complicating the measurement of a model's
logical reasoning capabilities. Other dynamic evaluation methods based on
strong models or manual efforts may introduce biases and incur high costs and
time demands, hindering large-scale application. To address these issues, we
propose TurtleBench. TurtleBench collects real user guesses from our online
Turtle Soup Puzzle platform that we developed. This approach allows for the
relatively dynamic generation of evaluation datasets, mitigating the risk of
model cheating while aligning assessments more closely with genuine user needs
for reasoning capabilities, thus enhancing the reliability of evaluations.
TurtleBench includes 1,532 user guesses along with the correctness of guesses
after annotation. Using this dataset, we thoroughly evaluated nine of the most
advanced LLMs available today. Notably, the OpenAI o1 series models did not
achieve leading results in these evaluations. We propose several hypotheses for
further research, such as "the latent reasoning of o1 utilizes trivial
Chain-of-Thought (CoT) techniques" and "increasing CoT length not only provides
reasoning benefits but also incurs noise costs."
