---
layout: publication
title: On Robustness Of Finetuned Transformer45;based NLP Models
authors: Neerudu Pavan Kalyan Reddy, Oota Subba Reddy, Marreddy Mounika, Kagita Venkateswara Rao, Gupta Manish
conference: "Arxiv"
year: 2023
bibkey: neerudu2023robustness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14453"}
  - {name: "Code", url: "https://github.com/PavanNeerudu/Robustness&#45;of&#45;Transformers&#45;models]"}
tags: ['Applications', 'BERT', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Security', 'Transformer']
---
Transformer45;based pretrained models like BERT GPT45;2 and T5 have been finetuned for a large number of natural language processing (NLP) tasks and have been shown to be very effective. However while finetuning what changes across layers in these models with respect to pretrained checkpoints is under45;studied. Further how robust are these models to perturbations in input text Does the robustness vary depending on the NLP task for which the models have been finetuned While there exists some work on studying the robustness of BERT finetuned for a few NLP tasks there is no rigorous study that compares this robustness across encoder only decoder only and encoder45;decoder models. In this paper we characterize changes between pretrained and finetuned language model representations across layers using two metrics CKA and STIR. Further we study the robustness of three language models (BERT GPT45;2 and T5) with eight different text perturbations on classification tasks from the General Language Understanding Evaluation (GLUE) benchmark and generation tasks like summarization free45;form generation and question generation. GPT45;2 representations are more robust than BERT and T5 across multiple types of input perturbation. Although models exhibit good robustness broadly dropping nouns verbs or changing characters are the most impactful. Overall this study provides valuable insights into perturbation45;specific weaknesses of popular Transformer45;based models which should be kept in mind when passing inputs. We make the code and models publicly available https://github.com/PavanNeerudu/Robustness&#45;of&#45;Transformers&#45;models].
