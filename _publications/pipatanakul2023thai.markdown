---
layout: publication
title: 'Typhoon: Thai Large Language Models'
authors: Kunat Pipatanakul, Phatrasek Jirabovonvisut, Potsawee Manakul, Sittipong Sripaisarnmongkol, Ruangsak Patomwong, Pathomporn Chokchainant, Kasima Tharnpipitchai
conference: "Arxiv"
year: 2023
bibkey: pipatanakul2023thai
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.13951'}
tags: ['Training Techniques', 'Model Architecture', 'Applications', 'Fine-Tuning', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
Typhoon is a series of Thai large language models (LLMs) developed
specifically for the Thai language. This technical report presents challenges
and insights in developing Thai LLMs, including data preparation, pretraining,
instruction-tuning, and evaluation. As one of the challenges of low-resource
languages is the amount of pretraining data, we apply continual training to
transfer existing world knowledge from a strong LLM. To evaluate the Thai
knowledge encapsulated in each model from the pretraining stage, we develop
ThaiExam, a benchmark based on examinations for high-school students and
investment professionals in Thailand. In addition, we fine-tune Typhoon to
follow Thai instructions, and we evaluate instruction-tuned models on Thai
instruction datasets as well as translation, summarization, and
question-answering tasks. Experimental results on a suite of Thai benchmarks
show that Typhoon outperforms all open-source Thai language models, and its
performance is on par with GPT-3.5 in Thai while having only 7 billion
parameters and being 2.62 times more efficient in tokenizing Thai text.
