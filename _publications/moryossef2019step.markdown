---
layout: publication
title: 'Step-by-step: Separating Planning From Realization In Neural Data-to-text
  Generation'
authors: Amit Moryossef, Yoav Goldberg, Ido Dagan
conference: Arxiv
year: 2019
citations: 49
bibkey: moryossef2019step
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.03396'}]
tags: [Language Modeling]
---
Data-to-text generation can be conceptually divided into two parts: ordering
and structuring the information (planning), and generating fluent language
describing the information (realization). Modern neural generation systems
conflate these two steps into a single end-to-end differentiable system. We
propose to split the generation process into a symbolic text-planning stage
that is faithful to the input, followed by a neural generation stage that
focuses only on realization. For training a plan-to-text generator, we present
a method for matching reference texts to their corresponding text plans. For
inference time, we describe a method for selecting high-quality text plans for
new inputs. We implement and evaluate our approach on the WebNLG benchmark. Our
results demonstrate that decoupling text planning from neural realization
indeed improves the system's reliability and adequacy while maintaining fluent
output. We observe improvements both in BLEU scores and in manual evaluations.
Another benefit of our approach is the ability to output diverse realizations
of the same input, paving the way to explicit control over the generated text
structure.