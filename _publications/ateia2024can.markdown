---
layout: publication
title: Can Open45;source Llms Compete With Commercial Models Exploring The Few45;shot Performance Of Current GPT Models In Biomedical Tasks
authors: Ateia Samy, Kruschwitz Udo
conference: "Arxiv"
year: 2024
bibkey: ateia2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13511"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'RAG']
---
Commercial large language models (LLMs) like OpenAIs GPT45;4 powering ChatGPT and Anthropics Claude 3 Opus have dominated natural language processing (NLP) benchmarks across different domains. New competing Open45;Source alternatives like Mixtral 8x7B or Llama 3 have emerged and seem to be closing the gap while often offering higher throughput and being less costly to use. Open45;Source LLMs can also be self45;hosted which makes them interesting for enterprise and clinical use cases where sensitive data should not be processed by third parties. We participated in the 12th BioASQ challenge which is a retrieval augmented generation (RAG) setting and explored the performance of current GPT models Claude 3 Opus GPT45;3.545;turbo and Mixtral 8x7b with in45;context learning (zero45;shot few45;shot) and QLoRa fine45;tuning. We also explored how additional relevant knowledge from Wikipedia added to the context45;window of the LLM might improve their performance. Mixtral 8x7b was competitive in the 1045;shot setting both with and without fine45;tuning but failed to produce usable results in the zero45;shot setting. QLoRa fine45;tuning and Wikipedia context did not lead to measurable performance gains. Our results indicate that the performance gap between commercial and open45;source models in RAG setups exists mainly in the zero45;shot setting and can be closed by simply collecting few45;shot examples for domain45;specific use cases. The code needed to rerun these experiments is available through GitHub.
