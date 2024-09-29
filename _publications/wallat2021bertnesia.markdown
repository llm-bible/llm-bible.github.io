---
layout: publication
title: BERTnesia Investigating the capture and forgetting of knowledge in BERT
authors: Wallat Jonas, Singh Jaspreet, Anand Avishek
conference: "Arxiv"
year: 2021
bibkey: wallat2021bertnesia
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.02902"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Probing complex language models has recently revealed several insights into linguistic and semantic patterns found in the learned representations. In this article we probe BERT specifically to understand and measure the relational knowledge it captures in its parametric memory. While probing for linguistic understanding is commonly applied to all layers of BERT as well as fine-tuned models this has not been done for factual knowledge. We utilize existing knowledge base completion tasks (LAMA) to probe every layer of pre-trained as well as fine-tuned BERT models(ranking question answering NER). Our findings show that knowledge is not just contained in BERTs final layers. Intermediate layers contribute a significant amount (17-60) to the total knowledge found. Probing intermediate layers also reveals how different types of knowledge emerge at varying rates. When BERT is fine-tuned relational knowledge is forgotten. The extent of forgetting is impacted by the fine-tuning objective and the training data. We found that ranking models forget the least and retain more knowledge in their final layer compared to masked language modeling and question-answering. However masked language modeling performed the best at acquiring new knowledge from the training data. When it comes to learning facts we found that capacity and fact density are key factors. We hope this initial work will spur further research into understanding the parametric memory of language models and the effect of training objectives on factual knowledge. The code to repeat the experiments is publicly available on GitHub.
