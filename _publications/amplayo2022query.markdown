---
layout: publication
title: Query Refinement Prompts for Closed-Book Long-Form Question Answering
authors: Amplayo Reinald Kim, Webster Kellie, Collins Michael, Das Dipanjan, Narayan Shashi
conference: "Arxiv"
year: 2022
bibkey: amplayo2022query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.17525"}
tags: ['Applications', 'Few Shot', 'Prompting', 'RAG']
---
Large language models (LLMs) have been shown to perform well in answering questions and in producing long-form texts both in few-shot closed-book settings. While the former can be validated using well-known evaluation metrics the latter is difficult to evaluate. We resolve the difficulties to evaluate long-form output by doing both tasks at once -- to do question answering that requires long-form answers. Such questions tend to be multifaceted i.e. they may have ambiguities and/or require information from multiple sources. To this end we define query refinement prompts that encourage LLMs to explicitly express the multifacetedness in questions and generate long-form answers covering multiple facets of the question. Our experiments on two long-form question answering datasets ASQA and AQuAMuSe show that using our prompts allows us to outperform fully finetuned models in the closed book setting as well as achieve results comparable to retrieve-then-generate open-book models.
