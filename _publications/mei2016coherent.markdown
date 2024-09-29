---
layout: publication
title: Coherent Dialogue With Attention45;based Language Models
authors: Mei Hongyuan, Bansal Mohit, Walter Matthew R.
conference: "Arxiv"
year: 2016
bibkey: mei2016coherent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1611.06997"}
tags: ['Attention Mechanism', 'Model Architecture', 'Reinforcement Learning', 'Transformer']
---
We model coherent conversation continuation via RNN45;based dialogue models equipped with a dynamic attention mechanism. Our attention45;RNN language model dynamically increases the scope of attention on the history as the conversation continues as opposed to standard attention (or alignment) models with a fixed input scope in a sequence45;to45;sequence model. This allows each generated word to be associated with the most relevant words in its corresponding conversation history. We evaluate the model on two popular dialogue datasets the open45;domain MovieTriples dataset and the closed45;domain Ubuntu Troubleshoot dataset and achieve significant improvements over the state45;of45;the45;art and baselines on several metrics including complementary diversity45;based metrics human evaluation and qualitative visualizations. We also show that a vanilla RNN with dynamic attention outperforms more complex memory models (e.g. LSTM and GRU) by allowing for flexible long45;distance memory. We promote further coherence via topic modeling45;based reranking.
