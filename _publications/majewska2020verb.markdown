---
layout: publication
title: 'Verb Knowledge Injection For Multilingual Event Processing'
authors: Majewska Olga, Vulić Ivan, Glavaš Goran, Ponti Edoardo M., Korhonen Anna
conference: "Proceedings of ACL-IJCNLP"
year: 2020
bibkey: majewska2020verb
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.15421"}
tags: ['Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
In parallel to their overwhelming success across NLP tasks, language ability of deep Transformer networks, pretrained via language modeling (LM) objectives has undergone extensive scrutiny. While probing revealed that these models encode a range of syntactic and semantic properties of a language, they are still prone to fall back on superficial cues and simple heuristics to solve downstream tasks, rather than leverage deeper linguistic knowledge. In this paper, we target one such area of their deficiency, verbal reasoning. We investigate whether injecting explicit information on verbs' semantic-syntactic behaviour improves the performance of LM-pretrained Transformers in event extraction tasks -- downstream tasks for which accurate verb processing is paramount. Concretely, we impart the verb knowledge from curated lexical resources into dedicated adapter modules (dubbed verb adapters), allowing it to complement, in downstream tasks, the language knowledge obtained during LM-pretraining. We first demonstrate that injecting verb knowledge leads to performance gains in English event extraction. We then explore the utility of verb adapters for event extraction in other languages: we investigate (1) zero-shot language transfer with multilingual Transformers as well as (2) transfer via (noisy automatic) translation of English verb-based lexical constraints. Our results show that the benefits of verb knowledge injection indeed extend to other languages, even when verb adapters are trained on noisily translated constraints.
