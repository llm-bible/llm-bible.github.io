---
layout: publication
title: Improving Language Models By Retrieving From Trillions Of Tokens
authors: Borgeaud Sebastian, Mensch Arthur, Hoffmann Jordan, Cai Trevor, Rutherford Eliza, Millican Katie, Driessche George Van Den, Lespiau Jean-baptiste, Damoc Bogdan, Clark Aidan, Casas Diego De Las, Guy Aurelia, Menick Jacob, Ring Roman, Hennigan Tom, Huang Saffron, Maggiore Loren, Jones Chris, Cassirer Albin, Brock Andy, Paganini Michela, Irving Geoffrey, Vinyals Oriol, Osindero Simon, Simonyan Karen, Rae Jack W., Elsen Erich, Sifre Laurent
conference: "Arxiv"
year: 2021
bibkey: borgeaud2021improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.04426"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
We enhance auto45;regressive language models by conditioning on document chunks retrieved from a large corpus based on local similarity with preceding tokens. With a 2 trillion token database our Retrieval45;Enhanced Transformer (RETRO) obtains comparable performance to GPT45;3 and Jurassic45;1 on the Pile despite using 25× fewer parameters. After fine45;tuning RETRO performance translates to downstream knowledge45;intensive tasks such as question answering. RETRO combines a frozen Bert retriever a differentiable encoder and a chunked cross45;attention mechanism to predict tokens based on an order of magnitude more data than what is typically consumed during training. We typically train RETRO from scratch yet can also rapidly RETROfit pre45;trained transformers with retrieval and still achieve good performance. Our work opens up new avenues for improving language models through explicit memory at unprecedented scale.
