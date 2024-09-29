---
layout: publication
title: 'Adversarial Databases Improve Success In Retrieval-based Large Language Models'
authors: Wu Sean, Koo Michael, Kao Li Yo, Black Andy, Blum Lesley, Scalzo Fabien, Kurtz Ira
conference: "Arxiv"
year: 2024
bibkey: wu2024adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14609"}
tags: ['RAG', 'Security']
---
Open-source LLMs have shown great potential as fine-tuned chatbots and demonstrate robust abilities in reasoning and surpass many existing benchmarks. Retrieval-Augmented Generation (RAG) is a technique for improving the performance of LLMs on tasks that the models werent explicitly trained on by leveraging external knowledge databases. Numerous studies have demonstrated the effectiveness of RAG to more successfully accomplish downstream tasks when using vector datasets that consist of relevant background information. It has been implicitly assumed by those in the field that if adversarial background information is utilized in this context that the success of using a RAG-based approach would be nonexistent or even negatively impact the results. To address this assumption we tested several open-source LLMs on the ability of RAG to improve their success in answering multiple-choice questions (MCQ) in the medical subspecialty field of Nephrology. Unlike previous studies we examined the effect of RAG in utilizing both relevant and adversarial background databases. We set up several open-source LLMs including Llama 3 Phi-3 Mixtral 8x7b Zephyr(beta) and Gemma 7B Instruct in a zero-shot RAG pipeline. As adversarial sources of information text from the Bible and a Random Words generated database were used for comparison. Our data show that most of the open-source LLMs improve their multiple-choice test-taking success as expected when incorporating relevant information vector databases. Surprisingly however adversarial Bible text significantly improved the success of many LLMs and even random word text improved test taking ability of some of the models. In summary our results demonstrate for the first time the countertintuitive ability of adversarial information datasets to improve the RAG-based LLM success.
