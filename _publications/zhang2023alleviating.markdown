---
layout: publication
title: Alleviating Hallucinations Of Large Language Models Through Induced Hallucinations
authors: Zhang Yue, Cui Leyang, Bi Wei, Shi Shuming
conference: "Arxiv"
year: 2023
bibkey: zhang2023alleviating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15710"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods']
---
Despite their impressive capabilities large language models (LLMs) have been observed to generate responses that include inaccurate or fabricated information a phenomenon commonly known as hallucination. In this work we propose a simple (textit)Induce-then-Contrast Decoding (ICD) strategy to alleviate hallucinations. We first construct a factually weak LLM by inducing hallucinations from the original LLMs. Then we penalize these induced hallucinations during decoding to enhance the factuality of the generated content. Concretely we determine the final next-token predictions by amplifying the predictions from the original model and downplaying the induced untruthful predictions via contrastive decoding. Experimental results on both discrimination-based and generation-based hallucination evaluation benchmarks such as TruthfulQA and (textscFActScore) demonstrate that our proposed ICD methods can effectively enhance the factuality of LLMs across various model sizes and families. For example when equipped with ICD Llama2-7B-Chat and Mistral-7B-Instruct achieve performance comparable to ChatGPT and GPT4 on TruthfulQA respectively.
