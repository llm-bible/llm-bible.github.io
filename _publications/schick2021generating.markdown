---
layout: publication
title: Generating Datasets With Pretrained Language Models
authors: "Timo Schick, Hinrich Sch\xFCtze"
conference: Arxiv
year: 2021
citations: 33
bibkey: schick2021generating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.07540'}]
tags: [RAG, Pre-Training]
---
To obtain high-quality sentence embeddings from pretrained language models
(PLMs), they must either be augmented with additional pretraining objectives or
finetuned on a large set of labeled text pairs. While the latter approach
typically outperforms the former, it requires great human effort to generate
suitable datasets of sufficient size. In this paper, we show how PLMs can be
leveraged to obtain high-quality sentence embeddings without the need for
labeled data, finetuning or modifications to the pretraining objective: We
utilize the generative abilities of large and high-performing PLMs to generate
entire datasets of labeled text pairs from scratch, which we then use for
finetuning much smaller and more efficient models. Our fully unsupervised
approach outperforms strong baselines on several semantic textual similarity
datasets.