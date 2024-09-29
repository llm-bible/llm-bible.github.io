---
layout: publication
title: End45;to45;end Synthetic Data Generation For Domain Adaptation Of Question Answering Systems
authors: Shakeri Siamak, Santos Cicero Nogueira Dos, Zhu Henry, Ng Patrick, Nan Feng, Wang Zhiguo, Nallapati Ramesh, Xiang Bing
conference: "Arxiv"
year: 2020
bibkey: shakeri2020end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.06028"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
We propose an end45;to45;end approach for synthetic QA data generation. Our model comprises a single transformer45;based encoder45;decoder network that is trained end45;to45;end to generate both answers and questions. In a nutshell we feed a passage to the encoder and ask the decoder to generate a question and an answer token45;by45;token. The likelihood produced in the generation process is used as a filtering score which avoids the need for a separate filtering model. Our generator is trained by fine45;tuning a pretrained LM using maximum likelihood estimation. The experimental results indicate significant improvements in the domain adaptation of QA models outperforming current state45;of45;the45;art methods.
