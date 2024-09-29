---
layout: publication
title: A Comprehensive Evaluation Of Neural SPARQL Query Generation From Natural Language Questions
authors: Diallo Papa Abdou Karim Karou, Reyd Samuel, Zouaq Amal
conference: "Arxiv"
year: 2023
bibkey: diallo2023comprehensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.07772"}
tags: ['Applications', 'Fine Tuning', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
In recent years the field of neural machine translation (NMT) for SPARQL query generation has witnessed significant growth. Incorporating the copy mechanism with traditional encoder-decoder architectures and using pre-trained encoder-decoders and large language models have set new performance benchmarks. This paper presents various experiments that replicate and expand upon recent NMT-based SPARQL generation studies comparing pre-trained language models (PLMs) non-pre-trained language models (NPLMs) and large language models (LLMs) highlighting the impact of question annotation and the copy mechanism and testing various fine-tuning methods using LLMs. In particular we provide a systematic error analysis of the models and test their generalization ability. Our study demonstrates that the copy mechanism yields significant performance enhancements for most PLMs and NPLMs. Annotating the data is pivotal to generating correct URIs with the tag-within strategy emerging as the most effective approach. Additionally our findings reveal that the primary source of errors stems from incorrect URIs in SPARQL queries that are sometimes replaced with hallucinated URIs when using base models. This does not happen using the copy mechanism but it sometimes leads to selecting wrong URIs among candidates. Finally the performance of the tested LLMs fell short of achieving the desired outcomes.
