---
layout: publication
title: ASPIRO Any45;shot Structured Parsing45;error45;induced Reprompting For Consistent Data45;to45;text Generation
authors: Vejvar Martin, Fujimoto Yasutaka
conference: "Arxiv"
year: 2023
bibkey: vejvar2023any
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17877"}
tags: ['Applications', 'Language Modeling', 'Prompting', 'RAG']
---
We present ASPIRO an approach for structured data verbalisation into short template sentences in zero to few45;shot settings. Unlike previous methods our approach prompts large language models (LLMs) to directly produce entity45;agnostic templates rather than relying on LLMs to faithfully copy the given example entities or validating/crafting the templates manually. We incorporate LLM re45;prompting triggered by algorithmic parsing checks as well as the PARENT metric induced consistency validation to identify and rectify template generation problems in real45;time. ASPIRO compared to direct LLM output averages 6637; parsing error rate reduction in generated verbalisations of RDF triples on the DART dataset. Our best 545;shot text45;davinci45;003 setup scoring BLEU of 50.62 METEOR of 45.16 BLEURT of 0.82 NUBIA of 0.87 and PARENT of 0.8962 on the Rel2Text dataset competes effectively with recent fine45;tuned pre45;trained language models.
