---
layout: publication
title: Uzh_clyp At Semeval-2023 Task 9 Head-first Fine-tuning And Chatgpt Data Generation For Cross-lingual Learning In Tweet Intimacy Prediction
authors: Michail Andrianos, Konstantinou Stefanos, Clematide Simon
conference: "Arxiv"
year: 2023
bibkey: michail2023uzh_clyp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.01194"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
This paper describes the submission of UZH_CLyp for the SemEval 2023 Task 9 Multilingual Tweet Intimacy Analysis. We achieved second-best results in all 10 languages according to the official Pearsons correlation regression evaluation measure. Our cross-lingual transfer learning approach explores the benefits of using a Head-First Fine-Tuning method (HeFiT) that first updates only the regression head parameters and then also updates the pre-trained transformer encoder parameters at a reduced learning rate. Additionally we study the impact of using a small set of automatically generated examples (in our case from ChatGPT) for low-resource settings where no human-labeled data is available. Our study shows that HeFiT stabilizes training and consistently improves results for pre-trained models that lack domain adaptation to tweets. Our study also shows a noticeable performance increase in cross-lingual learning when synthetic data is used confirming the usefulness of current text generation systems to improve zero-shot baseline results. Finally we examine how possible inconsistencies in the annotated data contribute to cross-lingual interference issues.
