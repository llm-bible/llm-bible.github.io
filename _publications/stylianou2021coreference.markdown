---
layout: publication
title: Corelm&#58; Coreference-aware Language Model Fine-tuning
authors: Stylianou Nikolaos, Vlahavas Ioannis
conference: "Arxiv"
year: 2021
bibkey: stylianou2021coreference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.02687"}
tags: ['Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Language Models are the underpin of all modern Natural Language Processing (NLP) tasks. The introduction of the Transformers architecture has contributed significantly into making Language Modeling very effective across many NLP task leading to significant advancements in the field. However Transformers come with a big computational cost which grows quadratically with respect to the input length. This presents a challenge as to understand long texts requires a lot of context. In this paper we propose a Fine-Tuning framework named CoreLM that extends the architecture of current Pretrained Language Models so that they incorporate explicit entity information. By introducing entity representations we make available information outside the contextual space of the model which results in a better Language Model for a fraction of the computational cost. We implement our approach using GPT2 and compare the fine-tuned model to the original. Our proposed model achieves a lower Perplexity in GUMBY and LAMBDADA datasets when compared to GPT2 and a fine-tuned version of GPT2 without any changes. We also compare the models performance in terms of Accuracy in LAMBADA and Childrens Book Test with and without the use of model-created coreference annotations.
