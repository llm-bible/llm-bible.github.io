---
layout: publication
title: Local Large Language Models For Complex Structured Medical Tasks
authors: Bumgardner V. K. Cody, Mullen Aaron, Armstrong Sam, Hickey Caylin, Talbert Jeff
conference: "Arxiv"
year: 2023
bibkey: bumgardner2023local
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.01727"}
tags: ['Applications', 'BERT', 'Ethics And Bias', 'Model Architecture', 'Training Techniques']
---
This paper introduces an approach that combines the language reasoning capabilities of large language models (LLMs) with the benefits of local training to tackle complex domain45;specific tasks. Specifically the authors demonstrate their approach by extracting structured condition codes from pathology reports. The proposed approach utilizes local LLMs which can be fine45;tuned to respond to specific generative instructions and provide structured outputs. The authors collected a dataset of over 150k uncurated surgical pathology reports containing gross descriptions final diagnoses and condition codes. They trained different model architectures including LLaMA BERT and LongFormer and evaluated their performance. The results show that the LLaMA45;based models significantly outperform BERT45;style models across all evaluated metrics even with extremely reduced precision. The LLaMA models performed especially well with large datasets demonstrating their ability to handle complex multi45;label tasks. Overall this work presents an effective approach for utilizing LLMs to perform domain45;specific tasks using accessible hardware with potential applications in the medical domain where complex data extraction and classification are required.
