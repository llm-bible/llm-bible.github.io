---
layout: publication
title: Self45;evaluation Improves Selective Generation In Large Language Models
authors: Ren Jie, Zhao Yao, Vu Tu, Liu Peter J., Lakshminarayanan Balaji
conference: "Arxiv"
year: 2023
bibkey: ren2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.09300"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Safe deployment of large language models (LLMs) may benefit from a reliable method for assessing their generated content to determine when to abstain or to selectively generate. While likelihood45;based metrics such as perplexity are widely employed recent research has demonstrated the limitations of using sequence45;level probability estimates given by LLMs as reliable indicators of generation quality. Conversely LLMs have demonstrated strong calibration at the token level particularly when it comes to choosing correct answers in multiple45;choice questions or evaluating true/false statements. In this work we reformulate open45;ended generation tasks into token45;level prediction tasks and leverage LLMs superior calibration at the token level. We instruct an LLM to self45;evaluate its answers employing either a multi45;way comparison or a point45;wise evaluation approach with the option to include a None of the above option to express the models uncertainty explicitly. We benchmark a range of scoring methods based on self45;evaluation and evaluate their performance in selective generation using TruthfulQA and TL;DR. Through experiments with PaLM45;2 and GPT45;3 we demonstrate that self45;evaluation based scores not only improve accuracy but also correlate better with the overall quality of generated content.
