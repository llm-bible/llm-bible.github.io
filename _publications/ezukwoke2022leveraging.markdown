---
layout: publication
title: 'Leveraging Pre-trained Models For Failure Analysis Triplets Generation'
authors: Ezukwoke Kenneth, Hoayek Anis, Batton-hubert Mireille, Boucher Xavier, Gounet Pascal, Adrian Jerome
conference: "Arxiv"
year: 2022
bibkey: ezukwoke2022leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.17497"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Pre-trained Language Models recently gained traction in the Natural Language Processing (NLP) domain for text summarization, generation and question-answering tasks. This stems from the innovation introduced in Transformer models and their overwhelming performance compared with Recurrent Neural Network Models (Long Short Term Memory (LSTM)). In this paper, we leverage the attention mechanism of pre-trained causal language models such as Transformer model for the downstream task of generating Failure Analysis Triplets (FATs) - a sequence of steps for analyzing defected components in the semiconductor industry. We compare different transformer models for this generative task and observe that Generative Pre-trained Transformer 2 (GPT2) outperformed other transformer model for the failure analysis triplet generation (FATG) task. In particular, we observe that GPT2 (trained on 1.5B parameters) outperforms pre-trained BERT, BART and GPT3 by a large margin on ROUGE. Furthermore, we introduce Levenshstein Sequential Evaluation metric (LESE) for better evaluation of the structured FAT data and show that it compares exactly with human judgment than existing metrics.
