---
layout: publication
title: PAL Program45;aided Language Models
authors: Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig
conference: "Arxiv"
year: 2022
bibkey: gao2022program
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2211.10435v2"}
  - {name: "Code", url: "http://reasonwithpal.com/"}
tags: ['Ethics And Bias', 'Has Code', 'Prompting']
---
Large language models (LLMs) have recently demonstrated an impressive ability to perform arithmetic and symbolic reasoning tasks when provided with a few examples at test time (few45;shot prompting). Much of this success can be attributed to prompting methods such as chain45;of45;thought which employ LLMs for both understanding the problem description by decomposing it into steps as well as solving each step of the problem. While LLMs seem to be adept at this sort of step45;by45;step decomposition LLMs often make logical and arithmetic mistakes in the solution part even when the problem is decomposed correctly. In this paper we present Program45;Aided Language models (PAL) a novel approach that uses the LLM to read natural language problems and generate programs as the intermediate reasoning steps but offloads the solution step to a runtime such as a Python interpreter. With PAL decomposing the natural language problem into runnable steps remains the only learning task for the LLM while solving is delegated to the interpreter. We demonstrate this synergy between a neural LLM and a symbolic interpreter across 13 mathematical symbolic and algorithmic reasoning tasks from BIG45;Bench Hard and other benchmarks. In all these natural language reasoning tasks generating code using an LLM and reasoning using a Python interpreter leads to more accurate results than much larger models. For example PAL using Codex achieves state45;of45;the45;art few45;shot accuracy on the GSM8K benchmark of math word problems surpassing PaLM45;540B which uses chain45;of45;thought by absolute 1537; top45;1. Our code and data are publicly available at http://reasonwithpal.com/ .
