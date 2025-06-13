---
layout: publication
title: 'Pearl: Personalizing Large Language Model Writing Assistants With Generation-calibrated Retrievers'
authors: Sheshera Mysore, Zhuoran Lu, Mengting Wan, Longqi Yang, Bahareh Sarrafzadeh, Steve Menezes, Tina Baghaee, Emmanuel Barajas Gonzalez, Jennifer Neville, Tara Safavi
conference: "Arxiv"
year: 2023
bibkey: mysore2023personalizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.09180'}
tags: ['Reinforcement Learning', 'Prompting', 'Efficiency and Optimization', 'Training Techniques']
---
Powerful large language models have facilitated the development of writing
assistants that promise to significantly improve the quality and efficiency of
composition and communication. However, a barrier to effective assistance is
the lack of personalization in LLM outputs to the author's communication style,
specialized knowledge, and values. In this paper, we address this challenge by
proposing Pearl, a LLM writing assistant personalized with a retriever that is
trained to be generation-calibrated for personalization. Generation calibration
ensures that our retriever selects historic user authored documents to augment
an LLM prompt such that they are likely to help an LLM generation better adhere
to a users' preferences. We propose two key novelties for training such a
retriever: (1) A training data selection method that identifies user requests
likely to benefit from personalization and documents that provide that benefit;
and (2) A scale-calibrating KL-divergence objective that ensures that our
retriever scores remain proportional to the downstream generation quality from
using the document for personalized generation. In a series of holistic
evaluations, we demonstrate the effectiveness of Pearl in generating long-form
texts on multiple social media datasets. Finally, we demonstrate how a
generation-calibrated retriever can double as a performance predictor --
detecting low quality retrieval, and improving potentially under-performing
outputs via revision with LLMs.
