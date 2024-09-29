---
layout: publication
title: 'Extended Mind Transformers'
authors: Klett Phoebe, Ahle Thomas
conference: "Arxiv"
year: 2024
bibkey: klett2024extended
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02332"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Pre-trained language models demonstrate general intelligence and common sense but long inputs quickly become a bottleneck for memorizing information at inference time. We resurface a simple method Memorizing Transformers (Wu et al. 2022) that gives the model access to a bank of pre-computed memories. We show that it is possible to fix many of the shortcomings of the original method such as the need for fine-tuning by critically assessing how positional encodings should be updated for the keys and values retrieved. This intuitive method uses the models own key/query system to select and attend to the most relevant memories at each generation step rather than using external embeddings. We demonstrate the importance of external information being retrieved in a majority of decoder layers contrary to previous work. We open source a new counterfactual long-range retrieval benchmark and show that Extended Mind Transformers outperform todays state of the art by 637; on average.
