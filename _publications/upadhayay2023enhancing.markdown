---
layout: publication
title: Taco Enhancing Cross45;lingual Transfer For Low45;resource Languages In Llms Through Translation45;assisted Chain45;of45;thought Processes
authors: Upadhayay Bibek, Behzadan Vahid
conference: "Arxiv"
year: 2023
bibkey: upadhayay2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10797"}
  - {name: "Code", url: "https://github.com/UNHSAILLab/TaCo&#125;"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Creating multilingual LLMs poses a significant challenge. Pretraining or fine45;tuning LLMs to adopt new languages is evidently very costly. Furthermore there exist limitations concerning benchmark datasets and the metrics used to measure model performance in multilingual settings. This paper proposes cost45;effective solutions to both aforementioned challenges. Firstly we introduce the Multilingual Instruction45;Tuning Dataset (MITS) comprised of Alpaca45;52K Dolly45;15K and Vicuna Benchmark translations into 132 languages. Secondly we propose a new method called emph123;TaCo Translation45;Assisted Cross45;Linguality125; which utilizes translations in a chain45;of45;thought process to instruction45;tune LLMs on new languages through a curriculum45;learning process. As a proof of concept we experimented with the instruction45;tuned Guanaco45;33B model performing further instruction tuning using our proposed TaCo method in three low45;resource languages and one high45;resource language. Our results indicate that the TaCo method impresses GPT45;4 with an 8237; score for a low45;resource language in the Vicuna Benchmark dataset doubling the performance in contrast to instruction tuning alone. Furthermore TaCo shows promise in creating multilingual LLMs even for low45;resource languages. We have released our datasets and model adaptersfootnote123;https://github.com/UNHSAILLab/TaCo&#125; encouraging the research community to utilize these resources to advance work on multilingual LLMs.
