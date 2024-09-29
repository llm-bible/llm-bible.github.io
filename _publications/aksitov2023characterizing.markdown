---
layout: publication
title: Characterizing Attribution And Fluency Tradeoffs For Retrieval45;augmented Large Language Models
authors: Aksitov Renat, Chang Chung-ching, Reitter David, Shakeri Siamak, Sung Yunhsuan
conference: "Arxiv"
year: 2023
bibkey: aksitov2023characterizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.05578"}
tags: ['Pretraining Methods', 'Prompting']
---
Despite recent progress it has been difficult to prevent semantic hallucinations in generative Large Language Models. One common solution to this is augmenting LLMs with a retrieval system and making sure that the generated output is attributable to the retrieved information. Given this new added constraint it is plausible to expect that the overall quality of the output will be affected for example in terms of fluency. Can scaling language models help Here we examine the relationship between fluency and attribution in LLMs prompted with retrieved evidence in knowledge45;heavy dialog settings. Our experiments were implemented with a set of auto45;metrics that are aligned with human preferences. They were used to evaluate a large set of generations produced under varying parameters of LLMs and supplied context. We show that larger models tend to do much better in both fluency and attribution and that (naively) using top45;k retrieval versus top45;1 retrieval improves attribution but hurts fluency. We next propose a recipe that could allow smaller models to both close the gap with larger models and preserve the benefits of top45;k retrieval while avoiding its drawbacks.
