---
layout: publication
title: 'Sentence Semantic Regression For Text Generation'
authors: Wang Wei, Li Piji, Zheng Hai-tao
conference: "Arxiv"
year: 2021
bibkey: wang2021sentence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.02984"}
tags: ['Applications', 'BERT', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
"Recall the classical text generation works, the generation framework can be briefly divided into two phases: \textbf\{idea reasoning\} and \textbf\{surface realization\}. The target of idea reasoning is to figure out the main idea which will be presented in the following talking/writing periods. Surface realization aims to arrange the most appropriate sentence to depict and convey the information distilled from the main idea. However, the current popular token-by-token text generation methods ignore this crucial process and suffer from many serious issues, such as idea/topic drift. To tackle the problems and realize this two-phase paradigm, we propose a new framework named Sentence Semantic Regression (\textbf\{SSR\}) based on sentence-level language modeling. For idea reasoning, two architectures \textbf\{SSR-AR\} and \textbf\{SSR-NonAR\} are designed to conduct sentence semantic regression autoregressively (like GPT2/3) and bidirectionally (like BERT). In the phase of surface realization, a mixed-granularity sentence decoder is designed to generate text with better consistency by jointly incorporating the predicted sentence-level main idea as well as the preceding contextual token-level information. We conduct experiments on four tasks of story ending prediction, story ending generation, dialogue generation, and sentence infilling. The results show that SSR can obtain better performance in terms of automatic metrics and human evaluation."
