---
layout: publication
title: 'Speechworthy Instruction-tuned Language Models'
authors: Hyundong Cho, Nicolaas Jedema, Leonardo F. R. Ribeiro, Karishma Sharma, Pedro Szekely, Alessandro Moschitti, Ruben Janssen, Jonathan May
conference: "Arxiv"
year: 2024
bibkey: cho2024speechworthy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14672'}
tags: ['RAG', 'Prompting']
---
Current instruction-tuned language models are exclusively trained with
textual preference data and thus are often not aligned with the unique
requirements of other modalities, such as speech. To better align language
models with the speech domain, we explore (i) prompting strategies grounded in
radio-industry best practices and (ii) preference learning using a novel
speech-based preference data of 20K samples, generated with a wide spectrum of
prompts that induce varying dimensions of speech-suitability and labeled by
annotators who listen to response pairs. Both human and automatic evaluation
show that both prompting and preference learning increase the
speech-suitability of popular instruction-tuned LLMs. Interestingly, we find
that prompting and preference learning can be additive; combining them achieves
the best win rates in head-to-head comparison, resulting in responses that are
preferred or tied to the base model in 76.2% of comparisons on average. Lastly,
we share lexical, syntactical, and qualitative analyses to showcase how each
method contributes to improving the speech-suitability of generated responses.
