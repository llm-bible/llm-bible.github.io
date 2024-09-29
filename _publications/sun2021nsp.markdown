---
layout: publication
title: NSP45;BERT A Prompt45;based Few45;shot Learner Through An Original Pre45;training Task45;45;next Sentence Prediction
authors: Sun Yi, Zheng Yu, Hao Chao, Qiu Hangping
conference: "Arxiv"
year: 2021
bibkey: sun2021nsp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.03564"}
tags: ['BERT', 'GPT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Using prompts to utilize language models to perform various downstream tasks also known as prompt45;based learning or prompt45;learning has lately gained significant success in comparison to the pre45;train and fine45;tune paradigm. Nonetheless virtually all prompt45;based methods are token45;level meaning they all utilize GPTs left45;to45;right language model or BERTs masked language model to perform cloze45;style tasks. In this paper we attempt to accomplish several NLP tasks in the zero45;shot scenario using a BERT original pre45;training task abandoned by RoBERTa and other models45;45;Next Sentence Prediction (NSP). Unlike token45;level techniques our sentence45;level prompt45;based method NSP45;BERT does not need to fix the length of the prompt or the position to be predicted allowing it to handle tasks such as entity linking with ease. Based on the characteristics of NSP45;BERT we offer several quick building templates for various downstream tasks. We suggest a two45;stage prompt method for word sense disambiguation tasks in particular. Our strategies for mapping the labels significantly enhance the models performance on sentence pair tasks. On the FewCLUE benchmark our NSP45;BERT outperforms other zero45;shot methods on most of these tasks and comes close to the few45;shot methods.
