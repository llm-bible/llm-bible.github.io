---
layout: publication
title: Babys Cothought Leveraging Large Language Models For Enhanced Reasoning In Compact Models
authors: Zhang Zheyu, Yang Han, Ma Bolei, Rügamer David, Nie Ercong
conference: "Arxiv"
year: 2023
bibkey: zhang2023babys
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.01684"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) demonstrate remarkable performance on a variety of natural language understanding (NLU) tasks primarily due to their in-context learning ability. This ability could be applied to building babylike models i.e. models at small scales improving training efficiency. In this paper we propose a CoThought pipeline which efficiently trains smaller baby language models (BabyLMs) by leveraging the Chain of Thought prompting of LLMs. Our pipeline restructures a dataset of less than 100M in size using GPT-3.5-turbo transforming it into task-oriented human-readable texts that are comparable to the school texts for language learners. The BabyLM is then pretrained on this restructured dataset in a RoBERTa fashion. In evaluations across 4 benchmarks our BabyLM outperforms the vanilla RoBERTa in 10 linguistic NLU and question-answering tasks by more than 3 points showing a superior ability to extract contextual information. These results suggest that compact LMs pretrained on small LLM-restructured data can better understand tasks and achieve improved performance.
