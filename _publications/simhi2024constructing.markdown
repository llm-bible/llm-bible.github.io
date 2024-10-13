---
layout: publication
title: 'Constructing Benchmarks And Interventions For Combating Hallucinations In Llms'
authors: Simhi Adi, Herzig Jonathan, Szpektor Idan, Belinkov Yonatan
conference: "Arxiv"
year: 2024
bibkey: simhi2024constructing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09971"}
  - {name: "Code", url: "https://github.com/technion-cs-nlp/hallucination-mitigation"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning']
---
Large language models (LLMs) are prone to hallucinations, which sparked a
widespread effort to detect and prevent them. Recent work attempts to mitigate
hallucinations by intervening in the model's generation, typically computing
representative vectors of hallucinations vs. grounded generations, for steering
the model's hidden states away from a hallucinatory state. However, common
studies employ different setups and do not properly separate different possible
causes of hallucinations, making interventions misguided. In this work, we
introduce a method for categorizing examples based on the model's prior
knowledge, named WACK. We construct WACK benchmarks that support interventions
in two settings: open-book and closed-book question answering. Using the
benchmarks, we perform an extensive investigation of the effect of different
choices for intervention, such as the intervened components, and how often and
how strongly to intervene. We find that intervention success varies depending
on the component, with the attention blocks performing well and the residual
stream proving detrimental to language modeling capabilities. We also show that
interventions can benefit from representative vectors collected before, rather
than after, a hallucination occurs. Finally, we introduce a new dynamic
intervention, which intervenes only if needed, and thus is more robust than
standard static interventions. The code is available at
https://github.com/technion-cs-nlp/hallucination-mitigation .
