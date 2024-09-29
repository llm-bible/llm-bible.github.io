---
layout: publication
title: Distilling Transformers For Neural Cross45;domain Search
authors: Clement Colin B., Wu Chen, Drain Dawn, Sundaresan Neel
conference: "Arxiv"
year: 2021
bibkey: clement2021distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.03322"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Pre45;trained transformers have recently clinched top spots in the gamut of natural language tasks and pioneered solutions to software engineering tasks. Even information retrieval has not been immune to the charm of the transformer though their large size and cost is generally a barrier to deployment. While there has been much work in streamlining caching and modifying transformer architectures for production here we explore a new direction distilling a large pre45;trained translation model into a lightweight bi45;encoder which can be efficiently cached and queried. We argue from a probabilistic perspective that sequence45;to45;sequence models are a conceptually ideal45;45;45;albeit highly impractical45;45;45;retriever. We derive a new distillation objective implementing it as a data augmentation scheme. Using natural language source code search as a case study for cross45;domain search we demonstrate the validity of this idea by significantly improving upon the current leader of the CodeSearchNet challenge a recent natural language code search benchmark.
