---
layout: publication
title: DS45;TOD Efficient Domain Specialization For Task Oriented Dialog
authors: Hung Chia-chien, Lauscher Anne, Ponzetto Simone Paolo, Glavaš Goran
conference: "Arxiv"
year: 2021
bibkey: hung2021ds
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08395"}
tags: ['BERT', 'Language Modeling', 'Masked Language Model', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent work has shown that self45;supervised dialog45;specific pretraining on large conversational datasets yields substantial gains over traditional language modeling (LM) pretraining in downstream task45;oriented dialog (TOD). These approaches however exploit general dialogic corpora (e.g. Reddit) and thus presumably fail to reliably embed domain45;specific knowledge useful for concrete downstream TOD domains. In this work we investigate the effects of domain specialization of pretrained language models (PLMs) for TOD. Within our DS45;TOD framework we first automatically extract salient domain45;specific terms and then use them to construct DomainCC and DomainReddit 45;45; resources that we leverage for domain45;specific pretraining based on (i) masked language modeling (MLM) and (ii) response selection (RS) objectives respectively. We further propose a resource45;efficient and modular domain specialization by means of domain adapters 45;45; additional parameter45;light layers in which we encode the domain knowledge. Our experiments with prominent TOD tasks 45;45; dialog state tracking (DST) and response retrieval (RR) 45;45; encompassing five domains from the MultiWOZ benchmark demonstrate the effectiveness of DS45;TOD. Moreover we show that the light45;weight adapter45;based specialization (1) performs comparably to full fine45;tuning in single domain setups and (2) is particularly suitable for multi45;domain specialization where besides advantageous computational footprint it can offer better TOD performance.
