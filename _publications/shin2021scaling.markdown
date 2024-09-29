---
layout: publication
title: "Scaling Law For Recommendation Models: Towards General-purpose User Representations"
authors: Shin Kyuyong, Kwak Hanock, Kim Su Young, Ramstrom Max Nihlen, Jeong Jisu, Ha Jung-woo, Kim Kyung-min
conference: "Arxiv"
year: 2021
bibkey: shin2021scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.11294"}
tags: ['BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Recent advancement of large-scale pretrained models such as BERT GPT-3 CLIP and Gopher has shown astonishing achievements across various task domains. Unlike vision recognition and language models studies on general-purpose user representation at scale still remain underexplored. Here we explore the possibility of general-purpose user representation learning by training a universal user encoder at large scales. We demonstrate that the scaling law is present in user representation learning areas where the training error scales as a power-law with the amount of computation. Our Contrastive Learning User Encoder (CLUE) optimizes task-agnostic objectives and the resulting user embeddings stretch our expectation of what is possible to do in various downstream tasks. CLUE also shows great transferability to other domains and companies as performances on an online experiment shows significant improvements in Click-Through-Rate (CTR). Furthermore we also investigate how the model performance is influenced by the scale factors such as training data size model capacity sequence length and batch size. Finally we discuss the broader impacts of CLUE in general.
