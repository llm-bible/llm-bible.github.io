---
layout: publication
title: How to Catch an AI Liar Lie Detection in Black-Box LLMs by Asking Unrelated Questions
authors: Pacchiardi Lorenzo, Chan Alex J., Mindermann Sören, Moscovitz Ilan, Pan Alexa Y., Gal Yarin, Evans Owain, Brauner Jan
conference: "Arxiv"
year: 2023
bibkey: pacchiardi2023how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15840"}
tags: ['ARXIV', 'GPT', 'LLM', 'Merging', 'Model Architecture', 'Prompt']
---
Large language models (LLMs) can lie which we define as outputting false statements despite knowing the truth in a demonstrable sense. LLMs might lie for example when instructed to output misinformation. Here we develop a simple lie detector that requires neither access to the LLMs activations (black-box) nor ground-truth knowledge of the fact in question. The detector works by asking a predefined set of unrelated follow-up questions after a suspected lie and feeding the LLMs yes/no answers into a logistic regression classifier. Despite its simplicity this lie detector is highly accurate and surprisingly general. When trained on examples from a single setting -- prompting GPT-3.5 to lie about factual questions -- the detector generalises out-of-distribution to (1) other LLM architectures (2) LLMs fine-tuned to lie (3) sycophantic lies and (4) lies emerging in real-life scenarios such as sales. These results indicate that LLMs have distinctive lie-related behavioural patterns consistent across architectures and contexts which could enable general-purpose lie detection.
