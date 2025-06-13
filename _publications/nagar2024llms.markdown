---
layout: publication
title: 'Llms Are Not Zero-shot Reasoners For Biomedical Information Extraction'
authors: Aishik Nagar, Viktor Schlegel, Thanh-tung Nguyen, Hao Li, Yuping Wu, Kuluhan Binici, Stefan Winkler
conference: "Arxiv"
year: 2024
bibkey: nagar2024llms
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.12249'}
tags: ['Reinforcement Learning', 'RAG', 'Prompting', 'Applications']
---
Large Language Models (LLMs) are increasingly adopted for applications in healthcare, reaching the performance of domain experts on tasks such as question answering and document summarisation. Despite their success on these tasks, it is unclear how well LLMs perform on tasks that are traditionally pursued in the biomedical domain, such as structured information extraction. To bridge this gap, in this paper, we systematically benchmark LLM performance in Medical Classification and Named Entity Recognition (NER) tasks. We aim to disentangle the contribution of different factors to the performance, particularly the impact of LLMs' task knowledge and reasoning capabilities, their (parametric) domain knowledge, and addition of external knowledge. To this end, we evaluate various open LLMs - including BioMistral and Llama-2 models - on a diverse set of biomedical datasets, using standard prompting, Chain of-Thought (CoT) and Self Consistency based reasoning as well as Retrieval-Augmented Generation (RAG) with PubMed and Wikipedia corpora. Counter intuitively, our results reveal that standard prompting consistently outperforms more complex techniques across both tasks, laying bare the limitations in the current application of CoT, self-consistency and RAG in the biomedical domain. Our findings suggest that advanced prompting methods developed for knowledge- or reasoning-intensive tasks, such as CoT or RAG, are not easily portable to biomedical tasks where precise structured outputs are required. This highlights the need for more effective integration of external knowledge and reasoning mechanisms in LLMs to enhance their performance in real-world biomedical applications.
