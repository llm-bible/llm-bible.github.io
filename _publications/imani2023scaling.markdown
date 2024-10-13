---
layout: publication
title: 'Glot500: Scaling Multilingual Corpora And Language Models To 500 Languages'
authors: Imani Ayyoob, Lin Peiqin, Kargaran Amir Hossein, Severini Silvia, Sabet Masoud Jalili, Kassner Nora, Ma Chunlan, Schmid Helmut, Martins André F. T., Yvon François, Schütze Hinrich
conference: "Arxiv"
year: 2023
bibkey: imani2023scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12182"}
  - {name: "Code", url: "https://github.com/cisnlp/Glot500"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
The NLP community has mainly focused on scaling Large Language Models (LLMs)
vertically, i.e., making them better for about 100 languages. We instead scale
LLMs horizontally: we create, through continued pretraining, Glot500-m, an LLM
that covers 511 predominantly low-resource languages. An important part of this
effort is to collect and clean Glot500-c, a corpus that covers these 511
languages and allows us to train Glot500-m. We evaluate Glot500-m on five
diverse tasks across these languages. We observe large improvements for both
high-resource and low-resource languages compared to an XLM-R baseline. Our
analysis shows that no single factor explains the quality of multilingual LLM
representations. Rather, a combination of factors determines quality including
corpus size, script, "help" from related languages and the total capacity of
the model. Our work addresses an important goal of NLP research: we should not
limit NLP to a small fraction of the world's languages and instead strive to
support as many languages as possible to bring the benefits of NLP technology
to all languages and cultures. Code, data and models are available at
https://github.com/cisnlp/Glot500.
