---
layout: publication
title: Long Context Question Answering Via Supervised Contrastive Learning
authors: Caciularu Avi, Dagan Ido, Goldberger Jacob, Cohan Arman
conference: "Arxiv"
year: 2021
bibkey: caciularu2021long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.08777"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Long-context question answering (QA) tasks require reasoning over a long document or multiple documents. Addressing these tasks often benefits from identifying a set of evidence spans (e.g. sentences) which provide supporting evidence for answering the question. In this work we propose a novel method for equipping long-context QA models with an additional sequence-level objective for better identification of the supporting evidence. We achieve this via an additional contrastive supervision signal in finetuning where the model is encouraged to explicitly discriminate supporting evidence sentences from negative ones by maximizing question-evidence similarity. The proposed additional loss exhibits consistent improvements on three different strong long-context transformer models across two challenging question answering benchmarks -- HotpotQA and QAsper.
