---
layout: publication
title: Have Llms Advanced Enough A Challenging Problem Solving Benchmark For Large Language Models
authors: Arora Daman, Singh Himanshu Gaurav, Mausam
conference: "Arxiv"
year: 2023
bibkey: arora2023have
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15074"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
The performance of large language models (LLMs) on existing reasoning benchmarks has significantly improved over the past years. In response we present JEEBench a considerably more challenging benchmark dataset for evaluating the problem solving abilities of LLMs. We curate 515 challenging pre45;engineering mathematics physics and chemistry problems from the highly competitive IIT JEE45;Advanced exam. Long45;horizon reasoning on top of deep in45;domain knowledge is essential for solving problems in this benchmark. Our evaluation on various open45;source and proprietary models reveals that the highest performance even after using techniques like self45;consistency self45;refinement and chain45;of45;thought prompting is less than 4037;. The typical failure modes of GPT45;4 the best model are errors in algebraic manipulation difficulty in grounding abstract concepts into mathematical equations accurately and failure in retrieving relevant domain45;specific concepts. We also observe that by mere prompting GPT45;4 is unable to assess risk introduced by negative marking for incorrect answers. For this we develop a post45;hoc confidence45;thresholding method over self45;consistency which enables effective response selection. We hope that our challenging benchmark will guide future re45;search in problem45;solving using LLMs.
