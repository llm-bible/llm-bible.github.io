---
layout: publication
title: 'Multireqa: A Cross-domain Evaluation For Retrieval Question Answering Models'
authors: Mandy Guo, Yinfei Yang, Daniel Cer, Qinlan Shen, Noah Constant
conference: Arxiv
year: 2020
citations: 18
bibkey: guo2020cross
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.02507'}]
tags: [Fine-Tuning, BERT]
---
Retrieval question answering (ReQA) is the task of retrieving a
sentence-level answer to a question from an open corpus (Ahmad et
al.,2019).This paper presents MultiReQA, anew multi-domain ReQA evaluation
suite com-posed of eight retrieval QA tasks drawn from publicly available QA
datasets. We provide the first systematic retrieval based evaluation over these
datasets using two supervised neural models, based on fine-tuning BERT
andUSE-QA models respectively, as well as a surprisingly strong information
retrieval baseline,BM25. Five of these tasks contain both train-ing and test
data, while three contain test data only. Performance on the five tasks with
train-ing data shows that while a general model covering all domains is
achievable, the best performance is often obtained by training exclusively on
in-domain data.