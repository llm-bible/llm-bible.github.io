---
layout: publication
title: MiniCheck Efficient Fact-Checking of LLMs on Grounding Documents
authors: Tang Liyan, Laban Philippe, Durrett Greg
conference: "Arxiv"
year: 2024
bibkey: tang2024minicheck
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10774"}
tags: ['ARXIV', 'Applications', 'GPT', 'LLM', 'Model Architecture', 'NLP', 'RAG']
---
Recognizing if LLM output can be grounded in evidence is central to many tasks in NLP retrieval-augmented generation summarization document-grounded dialogue and more. Current approaches to this kind of fact-checking are based on verifying each piece of a model generation against potential evidence using an LLM. However this process can be very computationally expensive requiring many calls to LLMs to check a single response. In this work we show how to build small models that have GPT-4-level performance but for 400x lower cost. We do this by constructing synthetic training data with GPT-4 which involves creating realistic yet challenging instances of factual errors via a structured generation procedure. Training on this data teaches models to check each fact in the claim and recognize synthesis of information across sentences. For evaluation we unify pre-existing datasets into a benchmark LLM-AggreFact collected from recent work on fact-checking and grounding LLM generations. Our best system MiniCheck-FT5 (770M parameters) outperforms all systems of comparable size and reaches GPT-4 accuracy. We release LLM-AggreFact code for data synthesis and models.
