---
layout: publication
title: Confidence Under the Hood An Investigation into the Confidence-Probability Alignment in Large Language Models
authors: Kumar Abhishek, Morabito Robert, Umbet Sanzhar, Kabbara Jad, Emami Ali
conference: "Arxiv"
year: 2024
bibkey: kumar2024confidence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16282"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG']
---
As the use of Large Language Models (LLMs) becomes more widespread understanding their self-evaluation of confidence in generated responses becomes increasingly important as it is integral to the reliability of the output of these models. We introduce the concept of Confidence-Probability Alignment that connects an LLMs internal confidence quantified by token probabilities to the confidence conveyed in the models response when explicitly asked about its certainty. Using various datasets and prompting techniques that encourage model introspection we probe the alignment between models internal and expressed confidence. These techniques encompass using structured evaluation scales to rate confidence including answer options when prompting and eliciting the models confidence level for outputs it does not recognize as its own. Notably among the models analyzed OpenAIs GPT-4 showed the strongest confidence-probability alignment with an average Spearmans hatrho of 0.42 across a wide range of tasks. Our work contributes to the ongoing efforts to facilitate risk assessment in the application of LLMs and to further our understanding of model trustworthiness.
