---
layout: publication
title: "Beyond Scale: The Diversity Coefficient As A Data Quality Metric For Variability In Natural Language Data"
authors: Miranda Brando, Lee Alycia, Sundar Sudharsan, Casasola Allison, Koyejo Sanmi
conference: "Published as workshop paper in the Data-centric Machine Learning Research"
year: 2023
bibkey: miranda2023beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.13840"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Current trends in pre-training Large Language Models (LLMs) primarily focus on the scaling of model and dataset size. While the quality of pre-training data is considered an important factor for training powerful LLMs it remains a nebulous concept that has not been rigorously characterized. To this end we propose a formalization of one key aspect of data quality -- measuring the variability of natural language data -- specifically via a measure we call the diversity coefficient. Our empirical analysis shows that the proposed diversity coefficient aligns with the intuitive properties of diversity and variability e.g. it increases as the number of latent concepts increases. Then we measure the diversity coefficient of publicly available pre-training datasets and demonstrate that their formal diversity is high compared to theoretical lower and upper bounds. Finally we conduct a comprehensive set of controlled interventional experiments with GPT-2 and LLaMAv2 that demonstrate the diversity coefficient of pre-training data characterizes useful aspects of downstream model evaluation performance -- totaling 44 models of various sizes (51M to 7B parameters). We conclude that our formal notion of diversity is an important aspect of data quality that captures variability and causally leads to improved evaluation performance.
