---
layout: publication
title: 'GPT-3 Models Are Few-shot Financial Reasoners'
authors: Raul Salles De Padua, Imran Qureshi, Mustafa U. Karakaplan
conference: "CS IT Conference Proceedings (2023) volume 13 number 12 pages 183-197"
year: 2023
bibkey: depadua2023gpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.13617"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Financial analysis is an important tool for evaluating company performance.
Practitioners work to answer financial questions to make profitable investment
decisions, and use advanced quantitative analyses to do so. As a result,
Financial Question Answering (QA) is a question answering task that requires
deep reasoning about numbers. Furthermore, it is unknown how well pre-trained
language models can reason in the financial domain. The current
state-of-the-art requires a retriever to collect relevant facts about the
financial question from the text and a generator to produce a valid financial
program and a final answer. However, recently large language models like GPT-3
have achieved state-of-the-art performance on wide variety of tasks with just a
few shot examples. We run several experiments with GPT-3 and find that a
separate retrieval model and logic engine continue to be essential components
to achieving SOTA performance in this task, particularly due to the precise
nature of financial questions and the complex information stored in financial
documents. With this understanding, our refined prompt-engineering approach on
GPT-3 achieves near SOTA accuracy without any fine-tuning.
