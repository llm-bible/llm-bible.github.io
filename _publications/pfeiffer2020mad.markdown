---
layout: publication
title: MAD45;X An Adapter45;based Framework For Multi45;task Cross45;lingual Transfer
authors: Pfeiffer Jonas, Vulić Ivan, Gurevych Iryna, Ruder Sebastian
conference: "Arxiv"
year: 2020
bibkey: pfeiffer2020mad
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.00052"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Tools', 'Training Techniques']
---
The main goal behind state45;of45;the45;art pre45;trained multilingual models such as multilingual BERT and XLM45;R is enabling and bootstrapping NLP applications in low45;resource languages through zero45;shot or few45;shot cross45;lingual transfer. However due to limited model capacity their transfer performance is the weakest exactly on such low45;resource languages and languages unseen during pre45;training. We propose MAD45;X an adapter45;based framework that enables high portability and parameter45;efficient transfer to arbitrary tasks and languages by learning modular language and task representations. In addition we introduce a novel invertible adapter architecture and a strong baseline method for adapting a pre45;trained multilingual model to a new language. MAD45;X outperforms the state of the art in cross45;lingual transfer across a representative set of typologically diverse languages on named entity recognition and causal commonsense reasoning and achieves competitive results on question answering. Our code and adapters are available at AdapterHub.ml
