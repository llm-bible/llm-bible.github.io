---
layout: publication
title: Make Pre45;trained Model Reversible From Parameter To Memory Efficient Fine45;tuning
authors: Liao Baohao, Tan Shaomu, Monz Christof
conference: "Arxiv"
year: 2023
bibkey: liao2023make
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00477"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Parameter45;efficient fine45;tuning (PEFT) of pre45;trained language models (PLMs) has emerged as a highly successful approach with training only a small number of parameters without sacrificing performance and becoming the de45;facto learning paradigm with the increasing size of PLMs. However existing PEFT methods are not memory45;efficient because they still require caching most of the intermediate activations for the gradient calculation akin to fine45;tuning. One effective way to reduce the activation memory is to apply a reversible model so the intermediate activations are not necessary to be cached and can be recomputed. Nevertheless modifying a PLM to its reversible variant is not straightforward since the reversible model has a distinct architecture from the currently released PLMs. In this paper we first investigate what is a key factor for the success of existing PEFT methods and realize that its essential to preserve the PLMs starting point when initializing a PEFT method. With this finding we propose memory45;efficient fine45;tuning (MEFT) that inserts adapters into a PLM preserving the PLMs starting point and making it reversible without additional pre45;training. We evaluate MEFT on the GLUE benchmark and five question45;answering tasks with various backbones BERT RoBERTa BART and OPT. MEFT significantly reduces the activation memory up to 8437; of full fine45;tuning with a negligible amount of trainable parameters. Moreover MEFT achieves the same score on GLUE and a comparable score on the question45;answering tasks as full fine45;tuning. A similar finding is also observed for the image classification task.
