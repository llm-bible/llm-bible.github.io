---
layout: publication
title: In45;context Principle Learning From Mistakes
authors: Zhang Tianjun, Madaan Aman, Gao Luyu, Zheng Steven, Mishra Swaroop, Yang Yiming, Tandon Niket, Alon Uri
conference: "Arxiv"
year: 2024
bibkey: zhang2024principle
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05403"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting']
---
In45;context learning (ICL also known as few45;shot prompting) has been the standard method of adapting LLMs to downstream tasks by learning from a few input45;output examples. Nonetheless all ICL45;based approaches only learn from correct input45;output pairs. In this paper we revisit this paradigm by learning more from the few given input45;output examples. We introduce Learning Principles (LEAP) First we intentionally induce the model to make mistakes on these few examples; then we reflect on these mistakes and learn explicit task45;specific principles from them which help solve similar problems and avoid common mistakes; finally we prompt the model to answer unseen test questions using the original few45;shot examples and these learned general principles. We evaluate LEAP on a wide range of benchmarks including multi45;hop question answering (Hotpot QA) textual QA (DROP) Big45;Bench Hard reasoning and math problems (GSM8K and MATH); in all these benchmarks LEAP improves the strongest available LLMs such as GPT45;3.545;turbo GPT45;4 GPT45;4 turbo and Claude45;2.1. For example LEAP improves over the standard few45;shot prompting using GPT45;4 by 7.537; in DROP and by 3.337; in HotpotQA. Importantly LEAP does not require any more input or examples than the standard few45;shot prompting settings.
