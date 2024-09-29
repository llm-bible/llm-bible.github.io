---
layout: publication
title: 'Slicerchat: Building A Local Chatbot For 3D Slicer'
authors: Barr Colton
conference: "Arxiv"
year: 2024
bibkey: barr2024building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11987"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
3D Slicer is a powerful platform for 3D data visualization and analysis but has a significant learning curve for new users. Generative AI applications such as ChatGPT have emerged as a potential method of bridging the gap between various sources of documentation using natural language. The limited exposure of LLM services to 3D Slicer documentation however means that ChatGPT and related services tend to suffer from significant hallucination. The objective of this project is to build a chatbot architecture called SlicerChat that is optimized to answer 3D Slicer related questions and able to run locally using an open-source model. The core research questions explored in this work revolve around the answer quality and speed differences due to fine-tuning model size and the type of domain knowledge included in the prompt. A prototype SlicerChat system was built as a custom extension in 3D Slicer based on the Code-Llama Instruct architecture. Models of size 1.1B 7B and 13B were fine-tuned using Low rank Adaptation and various sources of 3D Slicer documentation were compiled for use in a Retrieval Augmented Generation paradigm. Testing combinations of fine-tuning and model sizes on a benchmark dataset of five 3D Slicer questions revealed that fine-tuning had no impact on model performance or speed compared to the base architecture and that larger models performed better with a significant speed decrease. Experiments with adding 3D Slicer documentation to the prompt showed that Python sample code and Markdown documentation were the most useful information to include but that adding 3D Slicer scene data and questions taken from Discourse also improved model performance. In conclusion this project shows the potential for integrating a high quality local chatbot directly into 3D Slicer to help new users and experienced developers alike to more efficiently use the software.
