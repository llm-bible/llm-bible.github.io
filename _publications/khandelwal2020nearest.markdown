---
layout: publication
title: Nearest Neighbor Machine Translation
authors: Khandelwal Urvashi, Fan Angela, Jurafsky Dan, Zettlemoyer Luke, Lewis Mike
conference: "Arxiv"
year: 2020
bibkey: khandelwal2020nearest
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.00710"}
tags: ['Applications', 'RAG', 'Training Techniques']
---
We introduce k45;nearest45;neighbor machine translation (kNN45;MT) which predicts tokens with a nearest neighbor classifier over a large datastore of cached examples using representations from a neural translation model for similarity search. This approach requires no additional training and scales to give the decoder direct access to billions of examples at test time resulting in a highly expressive model that consistently improves performance across many settings. Simply adding nearest neighbor search improves a state45;of45;the45;art German45;English translation model by 1.5 BLEU. kNN45;MT allows a single model to be adapted to diverse domains by using a domain45;specific datastore improving results by an average of 9.2 BLEU over zero45;shot transfer and achieving new state45;of45;the45;art results 45;45; without training on these domains. A massively multilingual model can also be specialized for particular language pairs with improvements of 3 BLEU for translating from English into German and Chinese. Qualitatively kNN45;MT is easily interpretable; it combines source and target context to retrieve highly relevant examples.
