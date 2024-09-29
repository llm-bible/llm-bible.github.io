---
layout: publication
title: How To Catch An AI Liar Lie Detection In Black45;box Llms By Asking Unrelated Questions
authors: Pacchiardi Lorenzo, Chan Alex J., Mindermann Sören, Moscovitz Ilan, Pan Alexa Y., Gal Yarin, Evans Owain, Brauner Jan
conference: "Arxiv"
year: 2023
bibkey: pacchiardi2023how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15840"}
tags: ['GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) can lie which we define as outputting false statements despite knowing the truth in a demonstrable sense. LLMs might lie for example when instructed to output misinformation. Here we develop a simple lie detector that requires neither access to the LLMs activations (black45;box) nor ground45;truth knowledge of the fact in question. The detector works by asking a predefined set of unrelated follow45;up questions after a suspected lie and feeding the LLMs yes/no answers into a logistic regression classifier. Despite its simplicity this lie detector is highly accurate and surprisingly general. When trained on examples from a single setting 45;45; prompting GPT45;3.5 to lie about factual questions 45;45; the detector generalises out45;of45;distribution to (1) other LLM architectures (2) LLMs fine45;tuned to lie (3) sycophantic lies and (4) lies emerging in real45;life scenarios such as sales. These results indicate that LLMs have distinctive lie45;related behavioural patterns consistent across architectures and contexts which could enable general45;purpose lie detection.
