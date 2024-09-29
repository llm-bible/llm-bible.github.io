---
layout: publication
title: Future Sight Dynamic Story Generation With Large Pretrained Language Models
authors: Zimmerman Brian D., Sahu Gaurav, Vechtomova Olga
conference: "Arxiv"
year: 2022
bibkey: zimmerman2022future
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.09947"}
tags: ['Agentic', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Recent advances in deep learning research such as transformers have bolstered the ability for automated agents to generate creative texts similar to those that a human would write. By default transformer decoders can only generate new text with respect to previously generated text. The output distribution of candidate tokens at any position is conditioned on previously selected tokens using a self-attention mechanism to emulate the property of autoregression. This is inherently limiting for tasks such as controllable story generation where it may be necessary to condition on future plot events when writing a story. In this work we propose Future Sight a method for finetuning a pretrained generative transformer on the task of future conditioning. Transformer decoders are typically pretrained on the task of completing a context one token at a time by means of self-attention. Future Sight additionally enables a decoder to attend to an encoded future plot event. This motivates the decoder to expand on the context in a way that logically concludes with the provided future. During inference the future plot event can be written by a human author to steer the narrative being generated in a certain direction. We evaluate the efficacy of our approach on a story generation task with human evaluators.
