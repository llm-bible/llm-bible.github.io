---
layout: publication
title: ASPIRO Any-shot Structured Parsing-error-induced Reprompting For Consistent Data-to-text Generation
authors: Vejvar Martin, Fujimoto Yasutaka
conference: "Arxiv"
year: 2023
bibkey: vejvar2023aspiro
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17877"}
tags: ['Applications', 'Few Shot', 'Language Modeling', 'Prompting', 'RAG']
---
We present ASPIRO an approach for structured data verbalisation into short template sentences in zero to few-shot settings. Unlike previous methods our approach prompts large language models (LLMs) to directly produce entity-agnostic templates rather than relying on LLMs to faithfully copy the given example entities or validating/crafting the templates manually. We incorporate LLM re-prompting triggered by algorithmic parsing checks as well as the PARENT metric induced consistency validation to identify and rectify template generation problems in real-time. ASPIRO compared to direct LLM output averages 6637; parsing error rate reduction in generated verbalisations of RDF triples on the DART dataset. Our best 5-shot text-davinci-003 setup scoring BLEU of 50.62 METEOR of 45.16 BLEURT of 0.82 NUBIA of 0.87 and PARENT of 0.8962 on the Rel2Text dataset competes effectively with recent fine-tuned pre-trained language models.
