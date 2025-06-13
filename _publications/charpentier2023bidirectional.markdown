---
layout: publication
title: 'BRENT: Bidirectional Retrieval Enhanced Norwegian Transformer'
authors: Lucas Georges Gabriel Charpentier, Sondre Wold, David Samuel, Egil Rønningstad
conference: "Arxiv"
year: 2023
bibkey: charpentier2023bidirectional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.09649"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'Model Architecture', 'Language Modeling', 'Interpretability', 'Training Techniques', 'Pretraining Methods']
---
Retrieval-based language models are increasingly employed in
question-answering tasks. These models search in a corpus of documents for
relevant information instead of having all factual knowledge stored in its
parameters, thereby enhancing efficiency, transparency, and adaptability. We
develop the first Norwegian retrieval-based model by adapting the REALM
framework and evaluating it on various tasks. After training, we also separate
the language model, which we call the reader, from the retriever components,
and show that this can be fine-tuned on a range of downstream tasks. Results
show that retrieval augmented language modeling improves the reader's
performance on extractive question-answering, suggesting that this type of
training improves language models' general ability to use context and that this
does not happen at the expense of other abilities such as part-of-speech
tagging, dependency parsing, named entity recognition, and lemmatization. Code,
trained models, and data are made publicly available.
