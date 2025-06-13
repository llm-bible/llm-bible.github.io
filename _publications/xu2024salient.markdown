---
layout: publication
title: 'Salient Information Prompting To Steer Content In Prompt-based Abstractive Summarization'
authors: Lei Xu, Mohammed Asad Karim, Saket Dingliwal, Aparna Elangovan
conference: "Arxiv"
year: 2024
bibkey: xu2024salient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02741'}
  - {name: "Code", url: 'https://github.com/amazon-science/SigExt'}
tags: ['Has Code', 'RAG', 'Applications', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) can generate fluent summaries across domains
using prompting techniques, reducing the need to train models for summarization
applications. However, crafting effective prompts that guide LLMs to generate
summaries with the appropriate level of detail and writing style remains a
challenge. In this paper, we explore the use of salient information extracted
from the source document to enhance summarization prompts. We show that adding
keyphrases in prompts can improve ROUGE F1 and recall, making the generated
summaries more similar to the reference and more complete. The number of
keyphrases can control the precision-recall trade-off. Furthermore, our
analysis reveals that incorporating phrase-level salient information is
superior to word- or sentence-level. However, the impact on hallucination is
not universally positive across LLMs. To conduct this analysis, we introduce
Keyphrase Signal Extractor (SigExt), a lightweight model that can be finetuned
to extract salient keyphrases. By using SigExt, we achieve consistent ROUGE
improvements across datasets and open-weight and proprietary LLMs without any
LLM customization. Our findings provide insights into leveraging salient
information in building prompt-based summarization systems. We release our code
at \url\{https://github.com/amazon-science/SigExt\}
