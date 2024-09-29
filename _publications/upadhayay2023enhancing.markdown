---
layout: publication
title: Taco Enhancing Cross-lingual Transfer For Low-resource Languages In Llms Through Translation-assisted Chain-of-thought Processes
authors: Upadhayay Bibek, Behzadan Vahid
conference: "Arxiv"
year: 2023
bibkey: upadhayay2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10797"}
  - {name: "Code", url: "https://github.com/UNHSAILLab/TaCo\"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Creating multilingual LLMs poses a significant challenge. Pretraining or fine-tuning LLMs to adopt new languages is evidently very costly. Furthermore there exist limitations concerning benchmark datasets and the metrics used to measure model performance in multilingual settings. This paper proposes cost-effective solutions to both aforementioned challenges. Firstly we introduce the Multilingual Instruction-Tuning Dataset (MITS) comprised of Alpaca-52K Dolly-15K and Vicuna Benchmark translations into 132 languages. Secondly we propose a new method called (emph)TaCo Translation-Assisted Cross-Linguality which utilizes translations in a chain-of-thought process to instruction-tune LLMs on new languages through a curriculum-learning process. As a proof of concept we experimented with the instruction-tuned Guanaco-33B model performing further instruction tuning using our proposed TaCo method in three low-resource languages and one high-resource language. Our results indicate that the TaCo method impresses GPT-4 with an 8237; score for a low-resource language in the Vicuna Benchmark dataset doubling the performance in contrast to instruction tuning alone. Furthermore TaCo shows promise in creating multilingual LLMs even for low-resource languages. We have released our datasets and model adapters(footnote)https://github.com/UNHSAILLab/TaCo\} encouraging the research community to utilize these resources to advance work on multilingual LLMs.
