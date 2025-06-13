---
layout: publication
title: 'Personalisation Or Prejudice? Addressing Geographic Bias In Hate Speech Detection Using Debias Tuning In Large Language Models'
authors: Paloma Piot, Patricia Martín-rodilla, Javier Parapar
conference: "Arxiv"
year: 2025
bibkey: piot2025personalisation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.02252'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'Prompting']
---
Commercial Large Language Models (LLMs) have recently incorporated memory
features to deliver personalised responses. This memory retains details such as
user demographics and individual characteristics, allowing LLMs to adjust their
behaviour based on personal information. However, the impact of integrating
personalised information into the context has not been thoroughly assessed,
leading to questions about its influence on LLM behaviour. Personalisation can
be challenging, particularly with sensitive topics. In this paper, we examine
various state-of-the-art LLMs to understand their behaviour in different
personalisation scenarios, specifically focusing on hate speech. We prompt the
models to assume country-specific personas and use different languages for hate
speech detection. Our findings reveal that context personalisation
significantly influences LLMs' responses in this sensitive area. To mitigate
these unwanted biases, we fine-tune the LLMs by penalising inconsistent hate
speech classifications made with and without country or language-specific
context. The refined models demonstrate improved performance in both
personalised contexts and when no context is provided.
