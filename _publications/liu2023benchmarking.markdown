---
layout: publication
title: Benchmarking Generation and Evaluation Capabilities of Large Language Models for Instruction Controllable Summarization
authors: Liu Yixin, Fabbri Alexander R., Chen Jiawen, Zhao Yilun, Han Simeng, Joty Shafiq, Liu Pengfei, Radev Dragomir, Wu Chien-sheng, Cohan Arman
conference: "Arxiv"
year: 2023
bibkey: liu2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09184"}
tags: ['Applications']
---
While large language models (LLMs) can already achieve strong performance on standard generic summarization benchmarks their performance on more complex summarization task settings is less studied. Therefore we benchmark LLMs on instruction controllable text summarization where the model input consists of both a source article and a natural language requirement for desired summary characteristics. To this end we curate an evaluation-only dataset for this task setting and conduct human evaluations of five LLM-based systems to assess their instruction-following capabilities in controllable summarization. We then benchmark LLM-based automatic evaluation for this task with 4 different evaluation protocols and 11 LLMs resulting in 40 evaluation methods. Our study reveals that instruction controllable text summarization remains a challenging task for LLMs since (1) all LLMs evaluated still make factual and other types of errors in their summaries; (2) no LLM-based evaluation methods can achieve a strong alignment with human annotators when judging the quality of candidate summaries; (3) different LLMs show large performance gaps in summary generation and evaluation capabilities. We make our collected benchmark InstruSum publicly available to facilitate future research in this direction.
