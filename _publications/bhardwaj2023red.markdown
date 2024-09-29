---
layout: publication
title: Red45;teaming Large Language Models Using Chain Of Utterances For Safety45;alignment
authors: Bhardwaj Rishabh, Poria Soujanya
conference: "Arxiv"
year: 2023
bibkey: bhardwaj2023red
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.09662"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Responsible AI']
---
Larger language models (LLMs) have taken the world by storm with their massive multi45;tasking capabilities simply by optimizing over a next45;word prediction objective. With the emergence of their properties and encoded knowledge the risk of LLMs producing harmful outputs increases making them unfit for scalable deployment for the public. In this work we propose a new safety evaluation benchmark RED45;EVAL that carries out red45;teaming. We show that even widely deployed models are susceptible to the Chain of Utterances45;based (CoU) prompting jailbreaking closed source LLM45;based systems such as GPT45;4 and ChatGPT to unethically respond to more than 6537; and 7337; of harmful queries. We also demonstrate the consistency of the RED45;EVAL across 8 open45;source LLMs in generating harmful responses in more than 8637; of the red45;teaming attempts. Next we propose RED45;INSTRUCT45;45;An approach for the safety alignment of LLMs. It constitutes two phases 1) HARMFULQA data collection Leveraging CoU prompting we collect a dataset that consists of 1.9K harmful questions covering a wide range of topics 9.5K safe and 7.3K harmful conversations from ChatGPT; 2) SAFE45;ALIGN We demonstrate how the conversational dataset can be used for the safety alignment of LLMs by minimizing the negative log45;likelihood over helpful responses and penalizing over harmful responses by gradient accent over sample loss. Our model STARLING a fine45;tuned Vicuna45;7B is observed to be more safely aligned when evaluated on RED45;EVAL and HHH benchmarks while preserving the utility of the baseline models (TruthfulQA MMLU and BBH).
