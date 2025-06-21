---
layout: publication
title: If Beam Search Is The Answer, What Was The Question?
authors: Clara Meister, Tim Vieira, Ryan Cotterell
conference: Arxiv
year: 2020
citations: 22
bibkey: meister2020if
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.02650'}]
tags: [Reinforcement Learning, Language Modeling]
---
Quite surprisingly, exact maximum a posteriori (MAP) decoding of neural
language generators frequently leads to low-quality results. Rather, most
state-of-the-art results on language generation tasks are attained using beam
search despite its overwhelmingly high search error rate. This implies that the
MAP objective alone does not express the properties we desire in text, which
merits the question: if beam search is the answer, what was the question? We
frame beam search as the exact solution to a different decoding objective in
order to gain insights into why high probability under a model alone may not
indicate adequacy. We find that beam search enforces uniform information
density in text, a property motivated by cognitive science. We suggest a set of
decoding objectives that explicitly enforce this property and find that exact
decoding with these objectives alleviates the problems encountered when
decoding poorly calibrated language generation models. Additionally, we analyze
the text produced using various decoding strategies and see that, in our neural
machine translation experiments, the extent to which this property is adhered
to strongly correlates with BLEU.