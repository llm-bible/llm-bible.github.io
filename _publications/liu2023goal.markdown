---
layout: publication
title: 'Goal-oriented Prompt Attack And Safety Evaluation For Llms'
authors: Chengyuan Liu, Fubang Zhao, Lizhi Qing, Yangyang Kang, Changlong Sun, Kun Kuang, Fei Wu
conference: "Arxiv"
year: 2023
bibkey: liu2023goal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.11830"}
  - {name: "Code", url: "https://github.com/liuchengyuan123/CPAD"}
tags: ['Responsible AI', 'GPT', 'Applications', 'Model Architecture', 'Security', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) presents significant priority in text
understanding and generation. However, LLMs suffer from the risk of generating
harmful contents especially while being employed to applications. There are
several black-box attack methods, such as Prompt Attack, which can change the
behaviour of LLMs and induce LLMs to generate unexpected answers with harmful
contents. Researchers are interested in Prompt Attack and Defense with LLMs,
while there is no publicly available dataset with high successful attacking
rate to evaluate the abilities of defending prompt attack. In this paper, we
introduce a pipeline to construct high-quality prompt attack samples, along
with a Chinese prompt attack dataset called CPAD. Our prompts aim to induce
LLMs to generate unexpected outputs with several carefully designed prompt
attack templates and widely concerned attacking contents. Different from
previous datasets involving safety estimation, we construct the prompts
considering three dimensions: contents, attacking methods and goals.
Especially, the attacking goals indicate the behaviour expected after
successfully attacking the LLMs, thus the responses can be easily evaluated and
analysed. We run several popular Chinese LLMs on our dataset, and the results
show that our prompts are significantly harmful to LLMs, with around 70% attack
success rate to GPT-3.5. CPAD is publicly available at
https://github.com/liuchengyuan123/CPAD.
