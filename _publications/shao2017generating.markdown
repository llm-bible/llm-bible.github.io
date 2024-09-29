---
layout: publication
title: Generating High45;quality And Informative Conversation Responses With Sequence45;to45;sequence Models
authors: Shao Louis, Gouws Stephan, Britz Denny, Goldie Anna, Strope Brian, Kurzweil Ray
conference: "Arxiv"
year: 2017
bibkey: shao2017generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1701.03185"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Reinforcement Learning']
---
Sequence45;to45;sequence models have been applied to the conversation response generation problem where the source sequence is the conversation history and the target sequence is the response. Unlike translation conversation responding is inherently creative. The generation of long informative coherent and diverse responses remains a hard task. In this work we focus on the single turn setting. We add self45;attention to the decoder to maintain coherence in longer responses and we propose a practical approach called the glimpse45;model for scaling to large datasets. We introduce a stochastic beam45;search algorithm with segment45;by45;segment reranking which lets us inject diversity earlier in the generation process. We trained on a combined data set of over 2.3B conversation messages mined from the web. In human evaluation studies our method produces longer responses overall with a higher proportion rated as acceptable and excellent as length increases compared to baseline sequence45;to45;sequence models with explicit length45;promotion. A back45;off strategy produces better responses overall in the full spectrum of lengths.
