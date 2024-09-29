---
layout: publication
title: xCodeEval A Large Scale Multilingual Multitask Benchmark for Code Understanding Generation Translation and Retrieval
authors: Khan Mohammad Abdullah Matin, Bari M Saiful, Do Xuan Long, Wang Weishi, Parvez Md Rizwan, Joty Shafiq
conference: "Arxiv"
year: 2023
bibkey: khan2023xcodeeval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.03004"}
tags: ['Reinforcement Learning', 'Training Techniques']
---
Recently pre-trained large language models (LLMs) have shown impressive abilities in generating codes from natural language descriptions repairing buggy codes translating codes between languages and retrieving relevant code segments. However the evaluation of these models has often been performed in a scattered way on only one or two specific tasks in a few languages at a partial granularity (e.g. function) level and in many cases without proper training data. Even more concerning is that in most cases the evaluation of generated codes has been done in terms of mere lexical overlap with a reference code rather than actual execution. We introduce xCodeEval the largest executable multilingual multitask benchmark to date consisting of 25M document-level coding examples (16.5B tokens) from about 7.5K unique problems covering up to 11 programming languages with execution-level parallelism. It features a total of 7 tasks involving code understanding generation translation and retrieval. xCodeEval adopts an execution-based evaluation and offers a multilingual code execution engine ExecEval that supports unit test based execution in all the 11 languages. To address the challenge of balancing the distributions of text-code samples over multiple attributes in validation/test sets we propose a novel data splitting and a data selection schema based on the geometric mean and graph-theoretic principle. Our experiments with OpenAIs LLMs (zero-shot) and open-LLMs (zero-shot and fine-tuned) on the tasks and languages demonstrate xCodeEval to be quite challenging as per the current advancements in language models.
