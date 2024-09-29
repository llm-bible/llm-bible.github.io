---
layout: publication
title: Additive Interventions Yield Robust Multi-domain Machine Translation Models
authors: Rippeth Elijah, Post Matt
conference: "Arxiv"
year: 2022
bibkey: rippeth2022additive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.12727"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Additive interventions are a recently-proposed mechanism for controlling target-side attributes in neural machine translation. In contrast to tag-based approaches which manipulate the raw source sequence interventions work by directly modulating the encoder representation of all tokens in the sequence. We examine the role of additive interventions in a large-scale multi-domain machine translation setting and compare its performance in various inference scenarios. We find that while the performance difference is small between intervention-based systems and tag-based systems when the domain label matches the test domain intervention-based systems are robust to label error making them an attractive choice under label uncertainty. Further we find that the superiority of single-domain fine-tuning comes under question when training data size is scaled contradicting previous findings.
