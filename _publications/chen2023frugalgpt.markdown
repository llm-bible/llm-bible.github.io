---
layout: publication
title: FrugalGPT How to Use Large Language Models While Reducing Cost and Improving Performance
authors: Chen Lingjiao, Zaharia Matei, Zou James
conference: "Arxiv"
year: 2023
bibkey: chen2023frugalgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.05176"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Survey Paper', 'Tools']
---
There is a rapidly growing number of large language models (LLMs) that users can query for a fee. We review the cost associated with querying popular LLM APIs e.g. GPT-4 ChatGPT J1-Jumbo and find that these models have heterogeneous pricing structures with fees that can differ by two orders of magnitude. In particular using LLMs on large collections of queries and text can be expensive. Motivated by this we outline and discuss three types of strategies that users can exploit to reduce the inference cost associated with using LLMs 1) prompt adaptation 2) LLM approximation and 3) LLM cascade. As an example we propose FrugalGPT a simple yet flexible instantiation of LLM cascade which learns which combinations of LLMs to use for different queries in order to reduce cost and improve accuracy. Our experiments show that FrugalGPT can match the performance of the best individual LLM (e.g. GPT-4) with up to 98 cost reduction or improve the accuracy over GPT-4 by 4 with the same cost. The ideas and findings presented here lay a foundation for using LLMs sustainably and efficiently.
