---
layout: publication
title: Few45;shot Cross45;lingual Transfer For Prompting Large Language Models In Low45;resource Languages
authors: Toukmaji Christopher
conference: "Arxiv"
year: 2024
bibkey: toukmaji2024few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.06018"}
tags: ['Applications', 'Prompting', 'RAG', 'Training Techniques']
---
Large pre45;trained language models (PLMs) are at the forefront of advances in Natural Language Processing. One widespread use case of PLMs is prompting 45; or in45;context learning 45; where a user provides a description of a task and some completed examples of the task to a PLM as context before prompting the PLM to perform the task on a new example. Only the largest most capable PLMs are able to perform in45;context learning effectively and these models are typically trained with a predominantly English corpus leaving all other languages behind. The data limitations in most languages preclude the training of language45;specific PLMs capable of prompting. Albeit the surge in work of prompting settings it is still unclear how PLMs should be adapted cross45;lingually specifically for prompting. We evaluate the possible methods to adapt LLaMa a 7B parameter open45;source PLM mainly trained in English for prompting in low45;resource languages namely for Kinyarwanda Hausa and Luganda. We consider three methods few45;shot prompting (prompt) language45;adaptive fine45;tuning (LAFT) and neural machine translation (translate) and evaluate on abstractive summarization multi45;class topic classification and named45;entity recognition. Although LAFT carries the greatest compute cost and intuitively should lead to the best results our experiments exhibit that LAFT is only occasionally the optimal choice for adapting PLMs for prompting. Rather the translate and prompt settings are a compute45;efficient and cost45;effective method of few45;shot prompting for the selected low45;resource languages. We find that the results are task and language dependent but find that the prompting method is the best on average across all tasks and languages. Results show that the prompt setting performs better than both translating and LAFT with statistical significance for all shots when aggregated across all tasks and languages.
