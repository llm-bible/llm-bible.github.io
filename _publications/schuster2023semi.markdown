---
layout: publication
title: SEMQA Semi45;extractive Multi45;source Question Answering
authors: Schuster Tal, Lelkes Adam D., Sun Haitian, Gupta Jai, Berant Jonathan, Cohen William W., Metzler Donald
conference: "Arxiv"
year: 2023
bibkey: schuster2023semi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04886"}
tags: ['Applications', 'RAG', 'Reinforcement Learning']
---
Recently proposed long45;form question answering (QA) systems supported by large language models (LLMs) have shown promising capabilities. Yet attributing and verifying their generated abstractive answers can be difficult and automatically evaluating their accuracy remains an ongoing challenge. In this work we introduce a new QA task for answering multi45;answer questions by summarizing multiple diverse sources in a semi45;extractive fashion. Specifically Semi45;extractive Multi45;source QA (SEMQA) requires models to output a comprehensive answer while mixing factual quoted spans 45;45; copied verbatim from given input sources 45;45; and non45;factual free45;text connectors that glue these spans together into a single cohesive passage. This setting bridges the gap between the outputs of well45;grounded but constrained extractive QA systems and more fluent but harder to attribute fully abstractive answers. Particularly it enables a new mode for language models that leverages their advanced language generation capabilities while also producing fine in45;line attributions by45;design that are easy to verify interpret and evaluate. To study this task we create the first dataset of this kind QuoteSum with human45;written semi45;extractive answers to natural and generated questions and define text45;based evaluation metrics. Experimenting with several LLMs in various settings we find this task to be surprisingly challenging demonstrating the importance of QuoteSum for developing and studying such consolidation capabilities.
