---
layout: publication
title: Evaluating And Mitigating Linguistic Discrimination In Large Language Models
authors: Dong Guoliang, Wang Haoyu, Sun Jun, Wang Xinyu
conference: "Arxiv"
year: 2024
bibkey: dong2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18534"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
By training on text in various languages large language models (LLMs) typically possess multilingual support and demonstrate remarkable capabilities in solving tasks described in different languages. However LLMs can exhibit linguistic discrimination due to the uneven distribution of training data across languages. That is LLMs are hard to keep the consistency of responses when faced with the same task but depicted in different languages. In this study we first explore the consistency in the LLMs outputs responding to queries in various languages from two aspects safety and quality. We conduct this analysis with two datasets (AdvBench and NQ) based on four LLMs (Llama245;13b Gemma45;7b GPT45;3.545;turbo and Gemini45;pro). The results show that LLMs exhibit stronger human alignment capabilities with queries in English French Russian and Spanish (only 1.0437; of harmful queries successfully jailbreak on average) compared to queries in Bengali Georgian Nepali and Maithili (27.737; of harmful queries jailbreak successfully on average). Moreover for queries in English Danish Czech and Slovenian LLMs tend to produce responses with a higher quality (with 0.1494 F95;1 score on average) compared to the other languages. Upon these findings we propose LDFighter a similarity45;based voting to mitigate the linguistic discrimination in LLMs. LDFighter ensures consistent service for different language speakers. We evaluate LDFighter with both benign queries and harmful queries. The results show that LDFighter not only significantly reduces the jailbreak success rate but also improve the response quality on average demonstrating its effectiveness.
