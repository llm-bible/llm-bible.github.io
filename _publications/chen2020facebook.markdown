---
layout: publication
title: Facebook Ai's WMT20 News Translation Task Submission
authors: Peng-jen Chen et al.
conference: Arxiv
year: 2020
citations: 61
bibkey: chen2020facebook
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.08298'}]
tags: [Fine-Tuning]
---
This paper describes Facebook AI's submission to WMT20 shared news
translation task. We focus on the low resource setting and participate in two
language pairs, Tamil <-> English and Inuktitut <-> English, where there are
limited out-of-domain bitext and monolingual data. We approach the low resource
problem using two main strategies, leveraging all available data and adapting
the system to the target news domain. We explore techniques that leverage
bitext and monolingual data from all languages, such as self-supervised model
pretraining, multilingual models, data augmentation, and reranking. To better
adapt the translation system to the test domain, we explore dataset tagging and
fine-tuning on in-domain data. We observe that different techniques provide
varied improvements based on the available data of the language pair. Based on
the finding, we integrate these techniques into one training pipeline. For
En->Ta, we explore an unconstrained setup with additional Tamil bitext and
monolingual data and show that further improvement can be obtained. On the test
set, our best submitted systems achieve 21.5 and 13.7 BLEU for Ta->En and
En->Ta respectively, and 27.9 and 13.0 for Iu->En and En->Iu respectively.