---
layout: publication
title: 'Worldsense: A Synthetic Benchmark For Grounded Reasoning In Large Language Models'
authors: Benchekroun Youssef, Dervishi Megi, Ibrahim Mark, Gaya Jean-baptiste, Martinet Xavier, Mialon Grégoire, Scialom Thomas, Dupoux Emmanuel, Hupkes Dieuwke, Vincent Pascal
conference: "Arxiv"
year: 2023
bibkey: benchekroun2023synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.15930"}
tags: ['Ethics And Bias', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
We propose WorldSense a benchmark designed to assess the extent to which LLMs are consistently able to sustain tacit world models by testing how they draw simple inferences from descriptions of simple arrangements of entities. Worldsense is a synthetic benchmark with three problem types each with their own trivial control which explicitly avoids bias by decorrelating the abstract structure of problems from the vocabulary and expressions and by decorrelating all problem subparts with the correct response. We run our benchmark on three state-of-the-art chat-LLMs (GPT3.5 GPT4 and Llama2-chat) and show that these models make errors even with as few as three objects. Furthermore they have quite heavy response biases preferring certain responses irrespective of the question. Errors persist even with chain-of-thought prompting and in-context learning. Lastly we show that while finetuning on similar problems does result in substantial improvements -- within- and out-of-distribution -- the finetuned models do not generalise beyond a constraint problem space.
