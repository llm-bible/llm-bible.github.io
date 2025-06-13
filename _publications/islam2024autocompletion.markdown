---
layout: publication
title: 'Autocompletion Of Chief Complaints In The Electronic Health Records Using Large Language Models'
authors: K M Sajjadul Islam, Ayesha Siddika Nipu, Praveen Madiraju, Priya Deshpande
conference: "Arxiv"
year: 2024
bibkey: islam2024autocompletion
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.06088'}
tags: ['Language Modeling', 'Transformer', 'GPT', 'BERT', 'Model Architecture', 'Tools', 'Prompting', 'Applications', 'Pretraining Methods']
---
The Chief Complaint (CC) is a crucial component of a patient's medical record
as it describes the main reason or concern for seeking medical care. It
provides critical information for healthcare providers to make informed
decisions about patient care. However, documenting CCs can be time-consuming
for healthcare providers, especially in busy emergency departments. To address
this issue, an autocompletion tool that suggests accurate and well-formatted
phrases or sentences for clinical notes can be a valuable resource for triage
nurses. In this study, we utilized text generation techniques to develop
machine learning models using CC data. In our proposed work, we train a Long
Short-Term Memory (LSTM) model and fine-tune three different variants of
Biomedical Generative Pretrained Transformers (BioGPT), namely
microsoft/biogpt, microsoft/BioGPT-Large, and microsoft/BioGPT-Large-PubMedQA.
Additionally, we tune a prompt by incorporating exemplar CC sentences,
utilizing the OpenAI API of GPT-4. We evaluate the models' performance based on
the perplexity score, modified BERTScore, and cosine similarity score. The
results show that BioGPT-Large exhibits superior performance compared to the
other models. It consistently achieves a remarkably low perplexity score of
1.65 when generating CC, whereas the baseline LSTM model achieves the best
perplexity score of 170. Further, we evaluate and assess the proposed models'
performance and the outcome of GPT-4.0. Our study demonstrates that utilizing
LLMs such as BioGPT, leads to the development of an effective autocompletion
tool for generating CC documentation in healthcare settings.
