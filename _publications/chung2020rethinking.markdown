---
layout: publication
title: Rethinking Embedding Coupling In Pre45;trained Language Models
authors: Chung Hyung Won, Févry Thibault, Tsai Henry, Johnson Melvin, Ruder Sebastian
conference: "Arxiv"
year: 2020
bibkey: chung2020rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.12821"}
tags: ['Applications', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
We re45;evaluate the standard practice of sharing weights between input and output embeddings in state45;of45;the45;art pre45;trained language models. We show that decoupled embeddings provide increased modeling flexibility allowing us to significantly improve the efficiency of parameter allocation in the input embedding of multilingual models. By reallocating the input embedding parameters in the Transformer layers we achieve dramatically better performance on standard natural language understanding tasks with the same number of parameters during fine45;tuning. We also show that allocating additional capacity to the output embedding provides benefits to the model that persist through the fine45;tuning stage even though the output embedding is discarded after pre45;training. Our analysis shows that larger output embeddings prevent the models last layers from overspecializing to the pre45;training task and encourage Transformer representations to be more general and more transferable to other tasks and languages. Harnessing these findings we are able to train models that achieve strong performance on the XTREME benchmark without increasing the number of parameters at the fine45;tuning stage.
