---
layout: publication
title: Simplemtod A Simple Language Model For Multimodal Task45;oriented Dialogue With Symbolic Scene Representation
authors: Hemanthage Bhathiya, Dondrup Christian, Bartie Phil, Lemon Oliver
conference: "Arxiv"
year: 2023
bibkey: hemanthage2023simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.04907"}
tags: ['Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Transformer']
---
SimpleMTOD is a simple language model which recasts several sub45;tasks in multimodal task45;oriented dialogues as sequence prediction tasks. SimpleMTOD is built on a large45;scale transformer45;based auto45;regressive architecture which has already proven to be successful in uni45;modal task45;oriented dialogues and effectively leverages transfer learning from pre45;trained GPT45;2. In45;order to capture the semantics of visual scenes we introduce both local and de45;localized tokens for objects within a scene. De45;localized tokens represent the type of an object rather than the specific object itself and so possess a consistent meaning across the dataset. SimpleMTOD achieves a state45;of45;the45;art BLEU score (0.327) in the Response Generation sub45;task of the SIMMC 2.0 test45;std dataset while performing on par in other multimodal sub45;tasks Disambiguation Coreference Resolution and Dialog State Tracking. This is despite taking a minimalist approach for extracting visual (and non45;visual) information. In addition the model does not rely on task45;specific architectural changes such as classification heads.
