---
layout: publication
title: Can Transformers Learn Sequential Function Classes In Context
authors: Campbell Ryan, Guo Emma, Hu Evan, Vir Reya, Hsiao Ethan
conference: "Arxiv"
year: 2023
bibkey: campbell2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.12655"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security', 'Transformer']
---
In45;context learning (ICL) has revolutionized the capabilities of transformer models in NLP. In our project we extend the understanding of the mechanisms underpinning ICL by exploring whether transformers can learn from sequential non45;textual function class data distributions. We introduce a novel sliding window sequential function class and employ toy45;sized transformers with a GPT45;2 architecture to conduct our experiments. Our analysis indicates that these models can indeed leverage ICL when trained on non45;textual sequential function classes. Additionally our experiments with randomized y45;label sequences highlights that transformers retain some ICL capabilities even when the label associations are obfuscated. We provide evidence that transformers can reason with and understand sequentiality encoded within function classes as reflected by the effective learning of our proposed tasks. Our results also show that the performance deteriorated with increasing randomness in the labels though not to the extent one might expect implying a potential robustness of learned sequentiality against label noise. Future research may want to look into how previous explanations of transformers such as induction heads and task vectors relate to sequentiality in ICL in these toy examples. Our investigation lays the groundwork for further research into how transformers process and perceive sequential data.
