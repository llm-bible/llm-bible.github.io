---
layout: publication
title: 'Simplemtod: A Simple Language Model For Multimodal Task-oriented Dialogue With Symbolic Scene Representation'
authors: Hemanthage Bhathiya, Dondrup Christian, Bartie Phil, Lemon Oliver
conference: "Arxiv"
year: 2023
bibkey: hemanthage2023simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.04907"}
tags: ['Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Transformer']
---
"SimpleMTOD is a simple language model which recasts several sub-tasks in multimodal task-oriented dialogues as sequence prediction tasks. SimpleMTOD is built on a large-scale transformer-based auto-regressive architecture, which has already proven to be successful in uni-modal task-oriented dialogues, and effectively leverages transfer learning from pre-trained GPT-2. In-order to capture the semantics of visual scenes, we introduce both local and de-localized tokens for objects within a scene. De-localized tokens represent the type of an object rather than the specific object itself and so possess a consistent meaning across the dataset. SimpleMTOD achieves a state-of-the-art BLEU score (0.327) in the Response Generation sub-task of the SIMMC 2.0 test-std dataset while performing on par in other multimodal sub-tasks: Disambiguation, Coreference Resolution, and Dialog State Tracking. This is despite taking a minimalist approach for extracting visual (and non-visual) information. In addition the model does not rely on task-specific architectural changes such as classification heads."
