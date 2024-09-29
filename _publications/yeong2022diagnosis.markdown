---
layout: publication
title: Alzheimer's Diagnosis And Generation-based Chatbot Using Hierarchical Attention And Transformer
authors: Yeong Park Jun, Jong Shin Su, Hwan Choi Chang, Jae Lee Jung, Sang-il Choi
conference: "Arxiv"
year: 2022
bibkey: yeong2022diagnosis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.07703"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
In this paper we propose a natural language processing architecture that can handle tasks that previously required two models as one model. With a single model we analyze the language patterns and conversational context of Alzheimers patients and derive answers from two results patient classification and chatbot. If the patients language characteristics are identified by chatbots in daily life doctors can plan more precise diagnosis and treatment for early diagnosis. The proposed model is used to develop chatbots that replace questionnaires that required experts. There are two natural language processing tasks performed by the model. The first is a natural language classification that indicates with probability whether the patient has an illness and the second is to generate the next answer of the chatbot to the patients answer. In the first half a context vector which is a characteristic of patient utterance is extracted through a self-attention neural network. This context vector and chatbot (expert moderator) questions are entered together into the encoder to obtain a matrix containing the characteristics of the interaction between the questioner and the patient. The vectorized matrix becomes a probability value for classification of patients. Enter the matrix into the decoder with the next answer from the chatbot (the moderator) to generate the next utterance. As a result of learning this structure with DmentiaBanks cookie theft description corpus it was confirmed that the value of the loss function of the encoder and decoder was significantly reduced and converged. This shows that capturing the speech language pattern of Alzheimers disease patients can contribute to early diagnosis and longitudinal studies of the disease in the future.
