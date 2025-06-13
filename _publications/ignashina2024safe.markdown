---
layout: publication
title: 'Safe Training With Sensitive In-domain Data: Leveraging Data Fragmentation To Mitigate Linkage Attacks'
authors: Mariia Ignashina, Julia Ive
conference: "Arxiv"
year: 2024
bibkey: ignashina2024safe
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.19486'}
tags: ['Language Modeling', 'RAG', 'Security', 'Training Techniques', 'Model Architecture', 'BERT', 'Fine-Tuning', 'Applications', 'Pretraining Methods']
---
Current text generation models are trained using real data which can
potentially contain sensitive information, such as confidential patient
information and the like. Under certain conditions output of the training data
which they have memorised can be triggered, exposing sensitive data. To
mitigate against this risk we propose a safer alternative which sees fragmented
data in the form of domain-specific short phrases randomly grouped together
shared instead of full texts. Thus, text fragments that could re-identify an
individual cannot be reproduced by the model in one sequence, giving
significant protection against linkage attacks. We fine-tune several
state-of-the-art LLMs using meaningful syntactic chunks to explore their
utility. In particular, we fine-tune BERT-based models to predict two
cardiovascular diagnoses. Our results demonstrate the capacity of LLMs to
benefit from the pre-trained knowledge and deliver classification results when
fine-tuned with fragmented data comparable to fine-tuning with full training
data.
