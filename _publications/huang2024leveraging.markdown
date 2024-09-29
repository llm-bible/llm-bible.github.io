---
layout: publication
title: "Leveraging Large Language Models For Enhanced NLP Task Performance Through Knowledge Distillation And Optimized Training Strategies"
authors: Huang Yining, Tang Keke, Chen Meilian
conference: "Arxiv"
year: 2024
bibkey: huang2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09282"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Emerging Large Language Models (LLMs) like GPT-4 have revolutionized Natural Language Processing (NLP) showing potential in traditional tasks such as Named Entity Recognition (NER). Our study explores a three-phase training strategy that harnesses GPT-4s capabilities to enhance the BERT models performance on NER. Initially GPT-4 annotates a subset of the CONLL2003 and additional BBC dataset without fine-tuning. We then train BERT using a mix of original and LLM-annotated data analyzing the efficacy of LLM annotations against traditional methods. The second phase involves comparative experiments with different training regimens assessing the synergy between distilled and original data. We observe that sequential strategies particularly a simple mix of training first with distilled data followed by original data significantly boost performance. In the third phase we investigate various data blending techniques including sigmoid and power decay functions to optimize the training process further. Our results indicate that a strategic mix of distilled and original data markedly elevates the NER capabilities of BERT. Our approach presents a scalable methodology that reduces manual annotation costs and increases efficiency making it especially pertinent in resource-limited and closed-network environments. The study concludes that while the Simple Mix strategy yields the best results understanding its underlying mechanisms requires further research. Future work will also focus on refining prompt designs and enhancing annotation selection processes aiming to extend our methodology to diverse NLP tasks.
