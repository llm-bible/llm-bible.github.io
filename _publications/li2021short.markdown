---
layout: publication
title: A Short Study On Compressing Decoder45;based Language Models
authors: Li Tianda, Mesbahi Yassir El, Kobyzev Ivan, Rashid Ahmad, Mahmud Atif, Anchuri Nithin, Hajimolahoseini Habib, Liu Yang, Rezagholizadeh Mehdi
conference: "Arxiv"
year: 2021
bibkey: li2021short
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08460"}
tags: ['Attention Mechanism', 'BERT', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Quantization', 'Training Techniques']
---
Pre45;trained Language Models (PLMs) have been successful for a wide range of natural language processing (NLP) tasks. The state45;of45;the45;art of PLMs however are extremely large to be used on edge devices. As a result the topic of model compression has attracted increasing attention in the NLP community. Most of the existing works focus on compressing encoder45;based models (tiny45;BERT distilBERT distilRoBERTa etc) however to the best of our knowledge the compression of decoder45;based models (such as GPT45;2) has not been investigated much. Our paper aims to fill this gap. Specifically we explore two directions 1) we employ current state45;of45;the45;art knowledge distillation techniques to improve fine45;tuning of DistilGPT45;2. 2) we pre45;train a compressed GPT45;2 model using layer truncation and compare it against the distillation45;based method (DistilGPT2). The training time of our compressed model is significantly less than DistilGPT45;2 but it can achieve better performance when fine45;tuned on downstream tasks. We also demonstrate the impact of data cleaning on model performance.
