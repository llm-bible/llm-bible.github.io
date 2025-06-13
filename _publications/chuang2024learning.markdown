---
layout: publication
title: 'Learning To Route Llms With Confidence Tokens'
authors: Yu-neng Chuang, Helen Zhou, Prathusha Kameswara Sarma, Parikshit Gopalan, John Boccio, Sara Bolouki, Xia Hu
conference: "Arxiv"
year: 2024
bibkey: chuang2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13284"}
tags: ['Training Techniques', 'Applications', 'Reinforcement Learning']
---
Large language models (LLMs) have demonstrated impressive performance on
several tasks and are increasingly deployed in real-world applications.
However, especially in high-stakes settings, it becomes vital to know when the
output of an LLM may be unreliable. Depending on whether an answer is
trustworthy, a system can then choose to route the question to another expert,
or otherwise fall back on a safe default behavior. In this work, we study the
extent to which LLMs can reliably indicate confidence in their answers, and how
this notion of confidence can translate into downstream accuracy gains. We
propose Self-REF, a lightweight training strategy to teach LLMs to express
confidence in whether their answers are correct in a reliable manner. Self-REF
introduces confidence tokens into the LLM, from which a confidence score can be
extracted. Compared to conventional approaches such as verbalizing confidence
and examining token probabilities, we demonstrate empirically that confidence
tokens show significant improvements in downstream routing and rejection
learning tasks.
