---
layout: publication
title: For Generated text Is NLI-Neutral Text the Best Text
authors: Mersinias Michail, Mahowald Kyle
conference: "Arxiv"
year: 2023
bibkey: mersinias2023generated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.08577"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting']
---
We explore incorporating natural language inference (NLI) into the text generative pipeline by using a pre-trained NLI model to assess whether a generated sentence entails contradicts or is neutral to the prompt and preceding text. First we show that the NLI task is predictive of generation errors made by GPT-3. We use these results to develop an NLI-informed generation procedure for GPT-J. Then we evaluate these generations by obtaining human annotations on error types and overall quality. We find that an NLI strategy of maximizing entailment improves text generation when the nucleus sampling randomness parameter value is high while one which maximizes contradiction is in fact productive when the parameter value is low. Overall though we demonstrate that an NLI strategy of maximizing the neutral class provides the highest quality of generated text (significantly better than the vanilla generations) regardless of parameter value.
