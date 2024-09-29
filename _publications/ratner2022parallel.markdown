---
layout: publication
title: Parallel Context Windows For Large Language Models
authors: Ratner Nir, Levine Yoav, Belinkov Yonatan, Ram Ori, Magar Inbal, Abend Omri, Karpas Ehud, Shashua Amnon, Leyton-brown Kevin, Shoham Yoav
conference: "Arxiv"
year: 2022
bibkey: ratner2022parallel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10947"}
  - {name: "Code", url: "https://github.com/ai21labs/parallel&#45;context&#45;windows"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'Training Techniques', 'Transformer']
---
When applied to processing long text Large Language Models (LLMs) are limited by their context window. Existing efforts to address this limitation involve training specialized architectures and cannot be easily applied to off45;the45;shelf LLMs. We present Parallel Context Windows (PCW) a method that alleviates the context window restriction for any off45;the45;shelf LLM without further training. The key to the approach is to carve a long context into chunks (windows) restrict the attention mechanism to apply only within each window and re45;use the positional embeddings across the windows. Our main results test the PCW approach on in45;context learning with models that range in size between 750 million and 178 billion parameters and show substantial improvements for tasks with diverse input and output spaces. We show additional benefits in other settings where long context windows may be beneficial multi45;hop questions and retrieval45;augmented question answering with multiple retrieved documents. Our results highlight Parallel Context Windows as a promising method for applying off45;the45;shelf LLMs in a range of settings that require long text sequences. We make our code publicly available at https://github.com/ai21labs/parallel&#45;context&#45;windows.
