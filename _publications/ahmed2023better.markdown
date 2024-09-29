---
layout: publication
title: Better Patching Using LLM Prompting Via Self45;consistency
authors: Ahmed Toufique, Devanbu Premkumar
conference: "Arxiv"
year: 2023
bibkey: ahmed2023better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00108"}
tags: ['Interpretability And Explainability', 'Pretraining Methods', 'Prompting']
---
Large Language models (LLMs) can be induced to solve non45;trivial problems with few45;shot prompts including illustrative problem45;solution examples. Now if the few45;shots also include chain of thought (CoT) explanations which are of the form problem45;explanation45;solution LLMs will generate a explained solution and perform even better. Recently an exciting substantially better technique self45;consistency 1 (S45;C) has emerged based on the intuition that there are many plausible explanations for the right solution; when the LLM is sampled repeatedly to generate a pool of explanation45;solution pairs for a given problem the most frequently occurring solutions in the pool (ignoring the explanations) tend to be even more likely to be correct! Unfortunately the use of this highly45;performant S45;C (or even CoT) approach in software engineering settings is hampered by the lack of explanations; most software datasets lack explanations. In this paper we describe an application of the S45;C approach to program repair using the commit log on the fix as the explanation only in the illustrative few45;shots. We achieve state45;of45;the art results beating previous approaches to prompting45;based program repair on the MODIT dataset; we also find evidence suggesting that the correct commit messages are helping the LLM learn to produce better patches.
