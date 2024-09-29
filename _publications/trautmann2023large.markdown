---
layout: publication
title: Large Language Model Prompt Chaining For Long Legal Document Classification
authors: Trautmann Dietrich
conference: "Arxiv"
year: 2023
bibkey: trautmann2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04138"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Prompting is used to guide or steer a language model in generating an appropriate response that is consistent with the desired outcome. Chaining is a strategy used to decompose complex tasks into smaller manageable components. In this study we utilize prompt chaining for extensive legal document classification tasks which present difficulties due to their intricate domain45;specific language and considerable length. Our approach begins with the creation of a concise summary of the original document followed by a semantic search for related exemplar texts and their corresponding annotations from a training corpus. Finally we prompt for a label 45; based on the task 45; to assign by leveraging the in45;context learning from the few45;shot prompt. We demonstrate that through prompt chaining we can not only enhance the performance over zero45;shot but also surpass the micro45;F1 score achieved by larger models such as ChatGPT zero45;shot using smaller models.
