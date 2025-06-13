---
layout: publication
title: 'Predicting The Performance Of Black-box Llms Through Self-queries'
authors: Dylan Sam, Marc Finzi, J. Zico Kolter
conference: "Arxiv"
year: 2025
bibkey: sam2025predicting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01558"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Security', 'Training Techniques', 'Prompting']
---
As large language models (LLMs) are increasingly relied on in AI systems,
predicting when they make mistakes is crucial. While a great deal of work in
the field uses internal representations to interpret model behavior, these
representations are inaccessible when given solely black-box access through an
API. In this paper, we extract features of LLMs in a black-box manner by using
follow-up prompts and taking the probabilities of different responses as
representations to train reliable predictors of model behavior. We demonstrate
that training a linear model on these low-dimensional representations produces
reliable and generalizable predictors of model performance at the instance
level (e.g., if a particular generation correctly answers a question).
Remarkably, these can often outperform white-box linear predictors that operate
over a model's hidden state or the full distribution over its vocabulary. In
addition, we demonstrate that these extracted features can be used to evaluate
more nuanced aspects of a language model's state. For instance, they can be
used to distinguish between a clean version of GPT-4o-mini and a version that
has been influenced via an adversarial system prompt that answers
question-answering tasks incorrectly or introduces bugs into generated code.
Furthermore, they can reliably distinguish between different model
architectures and sizes, enabling the detection of misrepresented models
provided through an API (e.g., identifying if GPT-3.5 is supplied instead of
GPT-4o-mini).
