---
layout: publication
title: 'Forget Me Not: Reducing Catastrophic Forgetting For Domain Adaptation In Reading
  Comprehension'
authors: Y. Xu, X. Zhong, A. J. J. Yepes, J. H. Lau
conference: Arxiv
year: 2019
citations: 19
bibkey: xu2019forget
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.00202'}]
tags: [Fine-Tuning]
---
The creation of large-scale open domain reading comprehension data sets in
recent years has enabled the development of end-to-end neural comprehension
models with promising results. To use these models for domains with limited
training data, one of the most effective approach is to first pretrain them on
large out-of-domain source data and then fine-tune them with the limited target
data. The caveat of this is that after fine-tuning the comprehension models
tend to perform poorly in the source domain, a phenomenon known as catastrophic
forgetting. In this paper, we explore methods that overcome catastrophic
forgetting during fine-tuning without assuming access to data from the source
domain. We introduce new auxiliary penalty terms and observe the best
performance when a combination of auxiliary penalty terms is used to regularise
the fine-tuning process for adapting comprehension models. To test our methods,
we develop and release 6 narrow domain data sets that could potentially be used
as reading comprehension benchmarks.