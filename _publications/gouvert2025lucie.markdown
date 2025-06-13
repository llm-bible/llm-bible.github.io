---
layout: publication
title: 'The Lucie-7b LLM And The Lucie Training Dataset: Open Resources For Multilingual Language Generation'
authors: Olivier Gouvert, Julie Hunter, Jérôme Louradour, Christophe Cerisara, Evan Dufraisse, Yaya Sy, Laura Rivière, Jean-pierre Lorré, Openllm-france Community
conference: "Arxiv"
year: 2025
bibkey: gouvert2025lucie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.12294"}
tags: ['Training Techniques', 'Pretraining Methods', 'Ethics and Bias', 'Reinforcement Learning']
---
We present both the Lucie Training Dataset and the Lucie-7B foundation model.
The Lucie Training Dataset is a multilingual collection of textual corpora
centered around French and designed to offset anglo-centric biases found in
many datasets for large language model pretraining. Its French data is pulled
not only from traditional web sources, but also from French cultural heritage
documents, filling an important gap in modern datasets. Beyond French, which
makes up the largest share of the data, we added documents to support several
other European languages, including English, Spanish, German, and Italian.
Apart from its value as a resource for French language and culture, an
important feature of this dataset is that it prioritizes data rights by
minimizing copyrighted material. In addition, building on the philosophy of
past open projects, it is redistributed in the form used for training and its
processing is described on Hugging Face and GitHub. The Lucie-7B foundation
model is trained on equal amounts of data in French and English -- roughly 33%
each -- in an effort to better represent cultural aspects of French-speaking
communities. We also describe two instruction fine-tuned models,
Lucie-7B-Instruct-v1.1 and Lucie-7B-Instruct-human-data, which we release as
demonstrations of Lucie-7B in use. These models achieve promising results
compared to state-of-the-art models, demonstrating that an open approach
prioritizing data rights can still deliver strong performance. We see these
models as an initial step toward developing more performant, aligned models in
the near future. Model weights for Lucie-7B and the Lucie instruct models,
along with intermediate checkpoints for the former, are published on Hugging
Face, while model training and data preparation code is available on GitHub.
This makes Lucie-7B one of the first OSI compliant language models according to
the new OSI definition.
