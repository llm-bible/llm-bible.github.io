---
layout: publication
title: LEVER Learning To Verify Language-to-code Generation With Execution
authors: Ni Ansong, Iyer Srini, Radev Dragomir, Stoyanov Ves, Yih Wen-tau, Wang Sida I., Lin Xi Victoria
conference: "Arxiv"
year: 2023
bibkey: ni2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.08468"}
tags: ['Applications', 'Efficiency And Optimization', 'Pruning', 'Reinforcement Learning']
---
The advent of large language models trained on code (code LLMs) has led to significant progress in language-to-code generation. State-of-the-art approaches in this area combine LLM decoding with sample pruning and reranking using test cases or heuristics based on the execution results. However it is challenging to obtain test cases for many real-world language-to-code applications and heuristics cannot well capture the semantic features of the execution results such as data type and value range which often indicates the correctness of the program. In this work we propose LEVER a simple approach to improve language-to-code generation by learning to verify the generated programs with their execution results. Specifically we train verifiers to determine whether a program sampled from the LLMs is correct or not based on the natural language input the program itself and its execution results. The sampled programs are reranked by combining the verification score with the LLM generation probability and marginalizing over programs with the same execution results. On four datasets across the domains of table QA math QA and basic Python programming LEVER consistently improves over the base code LLMs(4.637; to 10.937; with code-davinci-002) and achieves new state-of-the-art results on all of them.
