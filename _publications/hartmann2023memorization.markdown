---
layout: publication
title: Sok Memorization In General-purpose Large Language Models
authors: Hartmann Valentin, Suri Anshuman, Bindschaedler Vincent, Evans David, Tople Shruti, West Robert
conference: "Arxiv"
year: 2023
bibkey: hartmann2023memorization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18362"}
tags: ['Applications', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Large Language Models (LLMs) are advancing at a remarkable pace with myriad applications under development. Unlike most earlier machine learning models they are no longer built for one specific application but are designed to excel in a wide range of tasks. A major part of this success is due to their huge training datasets and the unprecedented number of model parameters which allow them to memorize large amounts of information contained in the training data. This memorization goes beyond mere language and encompasses information only present in a few documents. This is often desirable since it is necessary for performing tasks such as question answering and therefore an important part of learning but also brings a whole array of issues from privacy and security to copyright and beyond. LLMs can memorize short secrets in the training data but can also memorize concepts like facts or writing styles that can be expressed in text in many different ways. We propose a taxonomy for memorization in LLMs that covers verbatim text facts ideas and algorithms writing styles distributional properties and alignment goals. We describe the implications of each type of memorization - both positive and negative - for model performance privacy security and confidentiality copyright and auditing and ways to detect and prevent memorization. We further highlight the challenges that arise from the predominant way of defining memorization with respect to model behavior instead of model weights due to LLM-specific phenomena such as reasoning capabilities or differences between decoding algorithms. Throughout the paper we describe potential risks and opportunities arising from memorization in LLMs that we hope will motivate new research directions.
