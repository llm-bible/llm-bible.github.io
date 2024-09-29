---
layout: publication
title: Scaling Sparse Fine45;tuning To Large Language Models
authors: Ansell Alan, Vulić Ivan, Sterz Hannah, Korhonen Anna, Ponti Edoardo M.
conference: "Arxiv"
year: 2024
bibkey: ansell2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.16405"}
  - {name: "Code", url: "https://github.com/AlanAnsell/peft"}
  - {name: "Code", url: "https://github.com/ducdauge/sft&#45;llm"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pruning', 'Quantization']
---
Large Language Models (LLMs) are difficult to fully fine45;tune (e.g. with instructions or human feedback) due to their sheer number of parameters. A family of parameter45;efficient sparse fine45;tuning methods have proven promising in terms of performance but their memory requirements increase proportionally to the size of the LLMs. In this work we scale sparse fine45;tuning to state45;of45;the45;art LLMs like LLaMA 2 7B and 13B. We propose SpIEL a novel sparse fine45;tuning method which for a desired density level maintains an array of parameter indices and the deltas of these parameters relative to their pretrained values. It iterates over (a) updating the active deltas (b) pruning indices (based on the change of magnitude of their deltas) and (c) regrowth of indices. For regrowth we explore two criteria based on either the accumulated gradients of a few candidate parameters or their approximate momenta estimated using the efficient SM3 optimizer. We experiment with instruction45;tuning of LLMs on standard dataset mixtures finding that SpIEL is often superior to popular parameter45;efficient fine45;tuning methods like LoRA (low45;rank adaptation) in terms of performance and comparable in terms of run time. We additionally show that SpIEL is compatible with both quantization and efficient optimizers to facilitate scaling to ever45;larger model sizes. We release the code for SpIEL at https://github.com/AlanAnsell/peft and for the instruction45;tuning experiments at https://github.com/ducdauge/sft&#45;llm.
