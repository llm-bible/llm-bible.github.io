---
layout: publication
title: Learning To Rewrite Generalized Llm45;generated Text Detection
authors: Hao Wei, Li Ran, Zhao Weiliang, Yang Junfeng, Mao Chengzhi
conference: "Arxiv"
year: 2024
bibkey: hao2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04237"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) can be abused at scale to create non45;factual content and spread disinformation. Detecting LLM45;generated content is essential to mitigate these risks but current classifiers often fail to generalize in open45;world contexts. Prior work shows that LLMs tend to rewrite LLM45;generated content less frequently which can be used for detection and naturally generalizes to unforeseen data. However we find that the rewriting edit distance between human and LLM content can be indistinguishable across domains leading to detection failures. We propose training an LLM to rewrite input text producing minimal edits for LLM45;generated content and more edits for human45;written text deriving a distinguishable and generalizable edit distance difference across different domains. Experiments on text from 21 independent domains and three popular LLMs (e.g. GPT45;4o Gemini and Llama45;3) show that our classifier outperforms the state45;of45;the45;art zero45;shot classifier by up to 20.637; on AUROC score and the rewriting classifier by 9.237; on F1 score. Our work suggests that LLM can effectively detect machine45;generated text if they are trained properly.
