---
layout: publication
title: 'Measuring The Robustness Of Reference-free Dialogue Evaluation Systems'
authors: Justin Vasselli, Adam Nohejl, Taro Watanabe
conference: "Arxiv"
year: 2025
bibkey: vasselli2025measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.06728"}
tags: ['Security', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications']
---
Advancements in dialogue systems powered by large language models (LLMs) have
outpaced the development of reliable evaluation metrics, particularly for
diverse and creative responses. We present a benchmark for evaluating the
robustness of reference-free dialogue metrics against four categories of
adversarial attacks: speaker tag prefixes, static responses, ungrammatical
responses, and repeated conversational context. We analyze metrics such as
DialogRPT, UniEval, and PromptEval -- a prompt-based method leveraging LLMs --
across grounded and ungrounded datasets. By examining both their correlation
with human judgment and susceptibility to adversarial attacks, we find that
these two axes are not always aligned; metrics that appear to be equivalent
when judged by traditional benchmarks may, in fact, vary in their scores of
adversarial responses. These findings motivate the development of nuanced
evaluation frameworks to address real-world dialogue challenges.
