---
layout: publication
title: 'Red-teaming Large Language Models Using Chain Of Utterances For Safety-alignment'
authors: Bhardwaj Rishabh, Poria Soujanya
conference: "Arxiv"
year: 2023
bibkey: bhardwaj2023red
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.09662"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Responsible AI']
---
'Larger language models (LLMs) have taken the world by storm with their massive multi-tasking capabilities simply by optimizing over a next-word prediction objective. With the emergence of their properties and encoded knowledge, the risk of LLMs producing harmful outputs increases, making them unfit for scalable deployment for the public. In this work, we propose a new safety evaluation benchmark RED-EVAL that carries out red-teaming. We show that even widely deployed models are susceptible to the Chain of Utterances-based (CoU) prompting, jailbreaking closed source LLM-based systems such as GPT-4 and ChatGPT to unethically respond to more than 65&#37; and 73&#37; of harmful queries. We also demonstrate the consistency of the RED-EVAL across 8 open-source LLMs in generating harmful responses in more than 86&#37; of the red-teaming attempts. Next, we propose RED-INSTRUCT--An approach for the safety alignment of LLMs. It constitutes two phases: 1) HARMFULQA data collection: Leveraging CoU prompting, we collect a dataset that consists of 1.9K harmful questions covering a wide range of topics, 9.5K safe and 7.3K harmful conversations from ChatGPT; 2) SAFE-ALIGN: We demonstrate how the conversational dataset can be used for the safety alignment of LLMs by minimizing the negative log-likelihood over helpful responses and penalizing over harmful responses by gradient accent over sample loss. Our model STARLING, a fine-tuned Vicuna-7B, is observed to be more safely aligned when evaluated on RED-EVAL and HHH benchmarks while preserving the utility of the baseline models (TruthfulQA, MMLU, and BBH).'
