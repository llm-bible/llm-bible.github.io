---
layout: publication
title: 'Bertnesia: Investigating The Capture And Forgetting Of Knowledge In BERT'
authors: Wallat Jonas, Singh Jaspreet, Anand Avishek
conference: "Arxiv"
year: 2020
bibkey: wallat2020investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.09313"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
"Probing complex language models has recently revealed several insights into linguistic and semantic patterns found in the learned representations. In this paper, we probe BERT specifically to understand and measure the relational knowledge it captures. We utilize knowledge base completion tasks to probe every layer of pre-trained as well as fine-tuned BERT (ranking, question answering, NER). Our findings show that knowledge is not just contained in BERT's final layers. Intermediate layers contribute a significant amount (17-60&#37;) to the total knowledge found. Probing intermediate layers also reveals how different types of knowledge emerge at varying rates. When BERT is fine-tuned, relational knowledge is forgotten but the extent of forgetting is impacted by the fine-tuning objective but not the size of the dataset. We found that ranking models forget the least and retain more knowledge in their final layer. We release our code on github to repeat the experiments."
