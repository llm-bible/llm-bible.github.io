---
layout: publication
title: 'STAR: A Simple Training-free Approach For Recommendations Using Large Language Models'
authors: Dong-ho Lee, Adam Kraft, Long Jin, Nikhil Mehta, Taibai Xu, Lichan Hong, Ed H. Chi, Xinyang Yi
conference: "Arxiv"
year: 2024
bibkey: lee2024simple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.16458'}
tags: ['Training Techniques', 'Tools', 'Model Architecture', 'Fine-Tuning', 'Survey Paper', 'Pretraining Methods']
---
Recent progress in large language models (LLMs) offers promising new
approaches for recommendation system tasks. While the current state-of-the-art
methods rely on fine-tuning LLMs to achieve optimal results, this process is
costly and introduces significant engineering complexities. Conversely, methods
that directly use LLMs without additional fine-tuning result in a large drop in
recommendation quality, often due to the inability to capture collaborative
information. In this paper, we propose a Simple Training-free Approach for
Recommendation (STAR), a framework that utilizes LLMs and can be applied to
various recommendation tasks without the need for fine-tuning, while
maintaining high quality recommendation performance. Our approach involves a
retrieval stage that uses semantic embeddings from LLMs combined with
collaborative user information to retrieve candidate items. We then apply an
LLM for pairwise ranking to enhance next-item prediction. Experimental results
on the Amazon Review dataset show competitive performance for next item
prediction, even with our retrieval stage alone. Our full method achieves
Hits@10 performance of +23.8% on Beauty, +37.5% on Toys & Games, and -1.8% on
Sports & Outdoors relative to the best supervised models. This framework offers
an effective alternative to traditional supervised models, highlighting the
potential of LLMs in recommendation systems without extensive training or
custom architectures.
