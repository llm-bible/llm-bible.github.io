---
layout: publication
title: 'Llms In The Loop: Leveraging Large Language Model Annotations For Active Learning In Low-resource Languages'
authors: Nataliia Kholodna, Sahib Julka, Mohammad Khodadadi, Muhammed Nurullah Gumus, Michael Granitzer
conference: "Arxiv"
year: 2024
bibkey: kholodna2024llms
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.02261'}
tags: ['RAG', 'Training Techniques', 'GPT', 'Tools', 'Model Architecture']
---
Low-resource languages face significant barriers in AI development due to
limited linguistic resources and expertise for data labeling, rendering them
rare and costly. The scarcity of data and the absence of preexisting tools
exacerbate these challenges, especially since these languages may not be
adequately represented in various NLP datasets. To address this gap, we propose
leveraging the potential of LLMs in the active learning loop for data
annotation. Initially, we conduct evaluations to assess inter-annotator
agreement and consistency, facilitating the selection of a suitable LLM
annotator. The chosen annotator is then integrated into a training loop for a
classifier using an active learning paradigm, minimizing the amount of queried
data required. Empirical evaluations, notably employing GPT-4-Turbo,
demonstrate near-state-of-the-art performance with significantly reduced data
requirements, as indicated by estimated potential cost savings of at least
42.45 times compared to human annotation. Our proposed solution shows promising
potential to substantially reduce both the monetary and computational costs
associated with automation in low-resource settings. By bridging the gap
between low-resource languages and AI, this approach fosters broader inclusion
and shows the potential to enable automation across diverse linguistic
landscapes.
