---
layout: publication
title: 'Options-aware Dense Retrieval For Multiple-choice Query Answering'
authors: Manish Singh, Manish Shrivastava
conference: "Arxiv"
year: 2025
bibkey: singh2025options
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.16111'}
tags: ['Transformer', 'ACL', 'RAG', 'Training Techniques', 'Model Architecture', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Long-context multiple-choice question answering tasks require robust
reasoning over extensive text sources. Since most of the pre-trained
transformer models are restricted to processing only a few hundred words at a
time, successful completion of such tasks often relies on the identification of
evidence spans, such as sentences, that provide supporting evidence for
selecting the correct answer. Prior research in this domain has predominantly
utilized pre-trained dense retrieval models, given the absence of supervision
to fine-tune the retrieval process. This paper proposes a novel method called
Options Aware Dense Retrieval (OADR) to address these challenges. ORDA uses an
innovative approach to fine-tuning retrieval by leveraging query-options
embeddings, which aim to mimic the embeddings of the oracle query (i.e., the
query paired with the correct answer) for enhanced identification of supporting
evidence. Through experiments conducted on the QuALITY benchmark dataset, we
demonstrate that our proposed model surpasses existing baselines in terms of
performance and accuracy.
