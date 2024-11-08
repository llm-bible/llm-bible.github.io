---
layout: publication
title: 'An LLM Feature-based Framework For Dialogue Constructiveness Assessment'
authors: Zhou Lexin, Farag Youmna, Vlachos Andreas
conference: "Arxiv"
year: 2024
bibkey: zhou2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14760"}
tags: ['Applications', 'Interpretability And Explainability', 'Prompting', 'Tools', 'Training Techniques']
---
Research on dialogue constructiveness assessment focuses on (i) analysing
conversational factors that influence individuals to take specific actions, win
debates, change their perspectives or broaden their open-mindedness and (ii)
predicting constructive outcomes following dialogues for such use cases. These
objectives can be achieved by training either interpretable feature-based
models (which often involve costly human annotations) or neural models such as
pre-trained language models (which have empirically shown higher task accuracy
but lack interpretability). We propose a novel LLM feature-based framework that
combines the strengths of feature-based and neural approaches while mitigating
their downsides, in assessing dialogue constructiveness. The framework first
defines a set of dataset-independent and interpretable linguistic features,
which can be extracted by both prompting an LLM and simple heuristics. Such
features are then used to train LLM feature-based models. We apply this
framework to three datasets of dialogue constructiveness and find that our LLM
feature-based models significantly outperform standard feature-based models and
neural models, and tend to learn more robust prediction rules instead of
relying on superficial shortcuts (as seen with neural models). Further, we
demonstrate that interpreting these LLM feature-based models can yield valuable
insights into what makes a dialogue constructive.
