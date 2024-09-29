---
layout: publication
title: Generating Rich Product Descriptions For Conversational E-commerce Systems
authors: Kedia Shashank, Mantha Aditya, Gupta Sneha, Guo Stephen, Achan Kannan
conference: "Companion Proceedings of the Web Conference"
year: 2021
bibkey: kedia2021generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.15298"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Through recent advancements in speech technologies and introduction of smart assistants such as Amazon Alexa Apple Siri and Google Home increasing number of users are interacting with various applications through voice commands. E-commerce companies typically display short product titles on their webpages either human-curated or algorithmically generated when brevity is required. However these titles are dissimilar from natural spoken language. For example Lucky Charms Gluten Free Break-fast Cereal 20.5 oz a box Lucky Charms Gluten Free is acceptable to display on a webpage while a similar title cannot be used in a voice based text-to-speech application. In such conversational systems an easy to comprehend sentence such as a 20.5 ounce box of lucky charms gluten free cereal is preferred. Compared to display devices where images and detailed product information can be presented to users short titles for products which convey the most important information are necessary when interfacing with voice assistants. We propose eBERT a sequence-to-sequence approach by further pre-training the BERT embeddings on an e-commerce product description corpus and then fine-tuning the resulting model to generate short natural spoken language titles from input web titles. Our extensive experiments on a real-world industry dataset as well as human evaluation of model output demonstrate that eBERT summarization outperforms comparable baseline models. Owing to the efficacy of the model a version of this model has been deployed in real-world setting.
